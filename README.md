# PROMETHEUS-K8S

The yamls presented here are intend to help on implement prometheus on a K8S cluster but mostly help understand all the details/components about this solution.
It's considered that you know how a k8s cluster works with all it's components and how to deploy applications on it.


### Metrics Providers

Inside [ metrics-providers ](metrics-providers) you will have the yamls for node-exporter and kube-state-metrics, both helps prometheus on collecting metrics from k8s resources and nodes.
Below we have more details including kubelet exposed metrics, note on the versions for the exposed metrics the naming can change between versions.

| Provider | Official docs | Exposed metrics |
| ---- | ---- | ---- |
| node_exporter | [ node_exporter github ](https://github.com/prometheus/node_exporter) | [ docs/node-exporter-v0.18.1.md ](docs/node-exporter-v0.18.1.md) |
| kube-state-metrics | [ kube-state-metrics github ](https://github.com/kubernetes/kube-state-metrics) | [ docs/kube-state-metrics-v1.7.2.md ](docs/kube-state-metrics-v1.7.2.md) |
| kubelet | [ k8s docs ](https://kubernetes.io/docs/tasks/debug-application-cluster/resource-usage-monitoring/) | [ docs/kubelet-metrics-v0.3.4.md ](docs/kubelet-metrics-v0.3.4.md) |


### Prometheus

Inside [ prometheus ](prometheus) we have alertmanager which is used to fire the alerts created by prometheus, those alerts can be to systems like email, slack and pagerduty.
Grafana will display us the metrics in form of dashboards, on [ grafana ](grafana) folder we have two sample of dashboards that can be implemented to view the resources usage of your cluster.

[ prometheus/prometheus-rules.yaml ](prometheus/prometheus-rules.yaml) was inspired on [ prometheus operator project ](https://github.com/coreos/prometheus-operator/blob/master/contrib/kube-prometheus/manifests/prometheus-rules.yaml) and modified accordingly to my needs. On this file we create the alerts that will be fired using alertmanager and help us identify problems before something can break or is already breaking and we are not aware. It uses promQL which could be a little difficult to understand at first.

[ prometheus/prometheus-conf.yaml ](prometheus/prometheus-conf.yaml) is the configuration file of prometheus, lets say it's heart, where all ties together.
  - It's defined what alertmanager instance to send the alerts to
  - It's defined what rules to load [ prometheus/prometheus-rules.yaml ](prometheus/prometheus-rules.yaml)
  - Where to scrape (pull metrics) from, there is a sample to scrape through service discovery and through static endpoints. It's worth to know that for applications we choosed to scrape from pods service discovery and to do so the following needs to be defined on the annotations section for your pod.
    ```
    annotations:
      # These annotations are required based on the way we currently
      # are getting metrics on Prometheus.
      prometheus.io/port: "place here the port of the exposed metrics for your service"
      prometheus.io/scrape: "true"
    ```

This solution is not storing the metrics anywhere, which means if you pod dies you will loose all metrics already collected. Here You could simply implement it with a PVC or use thanos as below.


### Prometheus with Thanos

Thanos was created to help store the metrics collected by prometheus, when we use it we no longer define prometheus as datasource on grafana, we define thanos-querier as datasource.
Read [ thanos documentation ](https://thanos.io/getting-started.md/) for further understanding of this solution.

Here instead of using a cloud providor like S3 bucket, we have an instance of [ minio ](https://docs.min.io/) running for simple purpose of demonstration of how to configure with a bucket.
For testing purposes we have minio deployment [ here ](minio).

So basically if you want to change where to store the metrics case you are on the cloud change details on this file [ config_bucket.yaml ](prometheus-thanos/config_bucket.yaml) (but remember to not store this file on your repo with the credential wide visible), this one is here just for test purposes. Also you need to convert it to base64 and change config_bucket.yaml section on this [ secret ](prometheus-thanos/thanos-config-bucket.yaml).



### Considerations
Hopes this gives you a head start on monitoring your k8s cluster, implementing this section by section helped me understand how all this works together.
