| metric  |  description  |  type |
| --- | --- | --- |
| kube_certificatesigningrequest_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_certificatesigningrequest_created  |  Unix creation timestamp | gauge |
| kube_certificatesigningrequest_condition  |  The number of each certificatesigningrequest condition | gauge |
| kube_certificatesigningrequest_cert_length  |  Length of the issued cert | gauge |
| kube_configmap_info  |  Information about configmap. | gauge |
| kube_configmap_created  |  Unix creation timestamp | gauge |
| kube_configmap_metadata_resource_version  |  Resource version representing a specific version of the configmap. | gauge |
| kube_cronjob_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_cronjob_info  |  Info about cronjob. | gauge |
| kube_cronjob_created  |  Unix creation timestamp | gauge |
| kube_cronjob_status_active  |  Active holds pointers to currently running jobs. | gauge |
| kube_cronjob_status_last_schedule_time  |  LastScheduleTime keeps information of when was the last time the job was successfully scheduled. | gauge |
| kube_cronjob_spec_suspend  |  Suspend flag tells the controller to suspend subsequent executions. | gauge |
| kube_cronjob_spec_starting_deadline_seconds  |  Deadline in seconds for starting the job if it misses scheduled time for any reason. | gauge |
| kube_cronjob_next_schedule_time  |  Next time the cronjob should be scheduled. The time after lastScheduleTime, or after the cron job's creation time if it's never been scheduled. Use this to determine if the job is delayed. | gauge |
| kube_daemonset_created  |  Unix creation timestamp | gauge |
| kube_daemonset_status_current_number_scheduled  |  The number of nodes running at least one daemon pod and are supposed to. | gauge |
| kube_daemonset_status_desired_number_scheduled  |  The number of nodes that should be running the daemon pod. | gauge |
| kube_daemonset_status_number_available  |  The number of nodes that should be running the daemon pod and have one or more of the daemon pod running and available | gauge |
| kube_daemonset_status_number_misscheduled  |  The number of nodes running a daemon pod but are not supposed to. | gauge |
| kube_daemonset_status_number_ready  |  The number of nodes that should be running the daemon pod and have one or more of the daemon pod running and ready. | gauge |
| kube_daemonset_status_number_unavailable  |  The number of nodes that should be running the daemon pod and have none of the daemon pod running and available | gauge |
| kube_daemonset_updated_number_scheduled  |  The total number of nodes that are running updated daemon pod | gauge |
| kube_daemonset_metadata_generation  |  Sequence number representing a specific generation of the desired state. | gauge |
| kube_daemonset_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_deployment_created  |  Unix creation timestamp | gauge |
| kube_deployment_status_replicas  |  The number of replicas per deployment. | gauge |
| kube_deployment_status_replicas_available  |  The number of available replicas per deployment. | gauge |
| kube_deployment_status_replicas_unavailable  |  The number of unavailable replicas per deployment. | gauge |
| kube_deployment_status_replicas_updated  |  The number of updated replicas per deployment. | gauge |
| kube_deployment_status_observed_generation  |  The generation observed by the deployment controller. | gauge |
| kube_deployment_spec_replicas  |  Number of desired pods for a deployment. | gauge |
| kube_deployment_spec_paused  |  Whether the deployment is paused and will not be processed by the deployment controller. | gauge |
| kube_deployment_spec_strategy_rollingupdate_max_unavailable  |  Maximum number of unavailable replicas during a rolling update of a deployment. | gauge |
| kube_deployment_spec_strategy_rollingupdate_max_surge  |  Maximum number of replicas that can be scheduled above the desired number of replicas during a rolling update of a deployment. | gauge |
| kube_deployment_metadata_generation  |  Sequence number representing a specific generation of the desired state. | gauge |
| kube_deployment_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_endpoint_info  |  Information about endpoint. | gauge |
| kube_endpoint_created  |  Unix creation timestamp | gauge |
| kube_endpoint_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_endpoint_address_available  |  Number of addresses available in endpoint. | gauge |
| kube_endpoint_address_not_ready  |  Number of addresses not ready in endpoint | gauge |
| kube_hpa_metadata_generation  |  The generation observed by the HorizontalPodAutoscaler controller. | gauge |
| kube_hpa_spec_max_replicas  |  Upper limit for the number of pods that can be set by the autoscaler; cannot be smaller than MinReplicas. | gauge |
| kube_hpa_spec_min_replicas  |  Lower limit for the number of pods that can be set by the autoscaler, default 1. | gauge |
| kube_hpa_status_current_replicas  |  Current number of replicas of pods managed by this autoscaler. | gauge |
| kube_hpa_status_desired_replicas  |  Desired number of replicas of pods managed by this autoscaler. | gauge |
| kube_hpa_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_hpa_status_condition  |  The condition of this autoscaler. | gauge |
| kube_ingress_info  |  Information about ingress. | gauge |
| kube_ingress_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_ingress_created  |  Unix creation timestamp | gauge |
| kube_ingress_metadata_resource_version  |  Resource version representing a specific version of ingress. | gauge |
| kube_ingress_path  |  Ingress host, paths and backend service information. | gauge |
| kube_job_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_job_info  |  Information about job. | gauge |
| kube_job_created  |  Unix creation timestamp | gauge |
| kube_job_spec_parallelism  |  The maximum desired number of pods the job should run at any given time. | gauge |
| kube_job_spec_completions  |  The desired number of successfully finished pods the job should be run with. | gauge |
| kube_job_spec_active_deadline_seconds  |  The duration in seconds relative to the startTime that the job may be active before the system tries to terminate it. | gauge |
| kube_job_status_succeeded  |  The number of pods which reached Phase Succeeded. | gauge |
| kube_job_status_failed  |  The number of pods which reached Phase Failed. | gauge |
| kube_job_status_active  |  The number of actively running pods. | gauge |
| kube_job_complete  |  The job has completed its execution. | gauge |
| kube_job_failed  |  The job has failed its execution. | gauge |
| kube_job_status_start_time  |  StartTime represents time when the job was acknowledged by the Job Manager. | gauge |
| kube_job_status_completion_time  |  CompletionTime represents time when the job was completed. | gauge |
| kube_job_owner  |  Information about the Job's owner. | gauge |
| kube_limitrange  |  Information about limit range. | gauge |
| kube_limitrange_created  |  Unix creation timestamp | gauge |
| kube_namespace_created  |  Unix creation timestamp | gauge |
| kube_namespace_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_namespace_status_phase  |  kubernetes namespace status phase. | gauge |
| kube_node_info  |  Information about a cluster node. | gauge |
| kube_node_created  |  Unix creation timestamp | gauge |
| kube_node_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_node_spec_unschedulable  |  Whether a node can schedule new pods. | gauge |
| kube_node_spec_taint  |  The taint of a cluster node. | gauge |
| kube_node_status_condition  |  The condition of a cluster node. | gauge |
| kube_node_status_phase  |  The phase the node is currently in. | gauge |
| kube_node_status_capacity  |  The capacity for different resources of a node. | gauge |
| kube_node_status_capacity_pods  |  The total pod resources of the node. | gauge |
| kube_node_status_capacity_cpu_cores  |  The total CPU resources of the node. | gauge |
| kube_node_status_capacity_memory_bytes  |  The total memory resources of the node. | gauge |
| kube_node_status_allocatable  |  The allocatable for different resources of a node that are available for scheduling. | gauge |
| kube_node_status_allocatable_pods  |  The pod resources of a node that are available for scheduling. | gauge |
| kube_node_status_allocatable_cpu_cores  |  The CPU resources of a node that are available for scheduling. | gauge |
| kube_node_status_allocatable_memory_bytes  |  The memory resources of a node that are available for scheduling. | gauge |
| kube_persistentvolumeclaim_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_persistentvolumeclaim_info  |  Information about persistent volume claim. | gauge |
| kube_persistentvolumeclaim_status_phase  |  The phase the persistent volume claim is currently in. | gauge |
| kube_persistentvolumeclaim_resource_requests_storage_bytes  |  The capacity of storage requested by the persistent volume claim. | gauge |
| kube_persistentvolumeclaim_access_mode  |  The access mode(s) specified by the persistent volume claim. | gauge |
| kube_persistentvolume_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_persistentvolume_status_phase  |  The phase indicates if a volume is available, bound to a claim, or released by a claim. | gauge |
| kube_persistentvolume_info  |  Information about persistentvolume. | gauge |
| kube_persistentvolume_capacity_bytes  |  Persistentvolume capacity in bytes. | gauge |
| kube_poddisruptionbudget_created  |  Unix creation timestamp | gauge |
| kube_poddisruptionbudget_status_current_healthy  |  Current number of healthy pods | gauge |
| kube_poddisruptionbudget_status_desired_healthy  |  Minimum desired number of healthy pods | gauge |
| kube_poddisruptionbudget_status_pod_disruptions_allowed  |  Number of pod disruptions that are currently allowed | gauge |
| kube_poddisruptionbudget_status_expected_pods  |  Total number of pods counted by this disruption budget | gauge |
| kube_poddisruptionbudget_status_observed_generation  |  Most recent generation observed when updating this PDB status | gauge |
| kube_pod_info  |  Information about pod. | gauge |
| kube_pod_start_time  |  Start time in unix timestamp for a pod. | gauge |
| kube_pod_completion_time  |  Completion time in unix timestamp for a pod. | gauge |
| kube_pod_owner  |  Information about the Pod's owner. | gauge |
| kube_pod_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_pod_created  |  Unix creation timestamp | gauge |
| kube_pod_status_scheduled_time  |  Unix timestamp when pod moved into scheduled status | gauge |
| kube_pod_status_phase  |  The pods current phase. | gauge |
| kube_pod_status_ready  |  Describes whether the pod is ready to serve requests. | gauge |
| kube_pod_status_scheduled  |  Describes the status of the scheduling process for the pod. | gauge |
| kube_pod_container_info  |  Information about a container in a pod. | gauge |
| kube_pod_init_container_info  |  Information about an init container in a pod. | gauge |
| kube_pod_container_status_waiting  |  Describes whether the container is currently in waiting state. | gauge |
| kube_pod_init_container_status_waiting  |  Describes whether the init container is currently in waiting state. | gauge |
| kube_pod_container_status_waiting_reason  |  Describes the reason the container is currently in waiting state. | gauge |
| kube_pod_init_container_status_waiting_reason  |  Describes the reason the init container is currently in waiting state. | gauge |
| kube_pod_container_status_running  |  Describes whether the container is currently in running state. | gauge |
| kube_pod_init_container_status_running  |  Describes whether the init container is currently in running state. | gauge |
| kube_pod_container_status_terminated  |  Describes whether the container is currently in terminated state. | gauge |
| kube_pod_init_container_status_terminated  |  Describes whether the init container is currently in terminated state. | gauge |
| kube_pod_container_status_terminated_reason  |  Describes the reason the container is currently in terminated state. | gauge |
| kube_pod_init_container_status_terminated_reason  |  Describes the reason the init container is currently in terminated state. | gauge |
| kube_pod_container_status_last_terminated_reason  |  Describes the last reason the container was in terminated state. | gauge |
| kube_pod_init_container_status_last_terminated_reason  |  Describes the last reason the init container was in terminated state. | gauge |
| kube_pod_container_status_ready  |  Describes whether the containers readiness check succeeded. | gauge |
| kube_pod_init_container_status_ready  |  Describes whether the init containers readiness check succeeded. | gauge |
| kube_pod_container_status_restarts_total  |  The number of container restarts per container. | counter |
| kube_pod_init_container_status_restarts_total  |  The number of restarts for the init container. | counter |
| kube_pod_container_resource_requests  |  The number of requested request resource by a container. | gauge |
| kube_pod_container_resource_limits  |  The number of requested limit resource by a container. | gauge |
| kube_pod_init_container_resource_limits  |  The number of requested limit resource by the init container. | gauge |
| kube_pod_container_resource_requests_cpu_cores  |  The number of requested cpu cores by a container. | gauge |
| kube_init_pod_container_resource_requests_cpu_cores  |  The number of requested cpu cores by an init container. | gauge |
| kube_pod_container_resource_requests_memory_bytes  |  The number of requested memory bytes by a container. | gauge |
| kube_pod_container_resource_limits_cpu_cores  |  The limit on cpu cores to be used by a container. | gauge |
| kube_pod_container_resource_limits_memory_bytes  |  The limit on memory to be used by a container in bytes. | gauge |
| kube_pod_spec_volumes_persistentvolumeclaims_info  |  Information about persistentvolumeclaim volumes in a pod. | gauge |
| kube_pod_spec_volumes_persistentvolumeclaims_readonly  |  Describes whether a persistentvolumeclaim is mounted read only. | gauge |
| kube_replicaset_created  |  Unix creation timestamp | gauge |
| kube_replicaset_status_replicas  |  The number of replicas per ReplicaSet. | gauge |
| kube_replicaset_status_fully_labeled_replicas  |  The number of fully labeled replicas per ReplicaSet. | gauge |
| kube_replicaset_status_ready_replicas  |  The number of ready replicas per ReplicaSet. | gauge |
| kube_replicaset_status_observed_generation  |  The generation observed by the ReplicaSet controller. | gauge |
| kube_replicaset_spec_replicas  |  Number of desired pods for a ReplicaSet. | gauge |
| kube_replicaset_metadata_generation  |  Sequence number representing a specific generation of the desired state. | gauge |
| kube_replicaset_owner  |  Information about the ReplicaSet's owner. | gauge |
| kube_replicaset_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_replicationcontroller_created  |  Unix creation timestamp | gauge |
| kube_replicationcontroller_status_replicas  |  The number of replicas per ReplicationController. | gauge |
| kube_replicationcontroller_status_fully_labeled_replicas  |  The number of fully labeled replicas per ReplicationController. | gauge |
| kube_replicationcontroller_status_ready_replicas  |  The number of ready replicas per ReplicationController. | gauge |
| kube_replicationcontroller_status_available_replicas  |  The number of available replicas per ReplicationController. | gauge |
| kube_replicationcontroller_status_observed_generation  |  The generation observed by the ReplicationController controller. | gauge |
| kube_replicationcontroller_spec_replicas  |  Number of desired pods for a ReplicationController. | gauge |
| kube_replicationcontroller_metadata_generation  |  Sequence number representing a specific generation of the desired state. | gauge |
| kube_resourcequota_created  |  Unix creation timestamp | gauge |
| kube_resourcequota  |  Information about resource quota. | gauge |
| kube_secret_info  |  Information about secret. | gauge |
| kube_secret_type  |  Type about secret. | gauge |
| kube_secret_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_secret_created  |  Unix creation timestamp | gauge |
| kube_secret_metadata_resource_version  |  Resource version representing a specific version of secret. | gauge |
| kube_service_info  |  Information about service. | gauge |
| kube_service_created  |  Unix creation timestamp | gauge |
| kube_service_spec_type  |  Type about service. | gauge |
| kube_service_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_service_spec_external_ip  |  Service external ips. One series for each ip | gauge |
| kube_service_status_load_balancer_ingress  |  Service load balancer ingress status | gauge |
| kube_statefulset_created  |  Unix creation timestamp | gauge |
| kube_statefulset_status_replicas  |  The number of replicas per StatefulSet. | gauge |
| kube_statefulset_status_replicas_current  |  The number of current replicas per StatefulSet. | gauge |
| kube_statefulset_status_replicas_ready  |  The number of ready replicas per StatefulSet. | gauge |
| kube_statefulset_status_replicas_updated  |  The number of updated replicas per StatefulSet. | gauge |
| kube_statefulset_status_observed_generation  |  The generation observed by the StatefulSet controller. | gauge |
| kube_statefulset_replicas  |  Number of desired pods for a StatefulSet. | gauge |
| kube_statefulset_metadata_generation  |  Sequence number representing a specific generation of the desired state for the StatefulSet. | gauge |
| kube_statefulset_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
| kube_statefulset_status_current_revision  |  Indicates the version of the StatefulSet used to generate Pods in the sequence [0,currentReplicas). | gauge |
| kube_statefulset_status_update_revision  |  Indicates the version of the StatefulSet used to generate Pods in the sequence [replicas-updatedReplicas,replicas) | gauge |
| kube_storageclass_info  |  Information about storageclass. | gauge |
| kube_storageclass_created  |  Unix creation timestamp | gauge |
| kube_storageclass_labels  |  Kubernetes labels converted to Prometheus labels. | gauge |
