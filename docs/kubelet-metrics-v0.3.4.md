| metric  |  description | type |
| --- | --- | --- |
| apiserver_audit_event_total  |  Counter of audit events generated and sent to the audit backend.| counter |
| apiserver_audit_requests_rejected_total  |  Counter of apiserver requests rejected due to an error in audit logging backend.| counter |
| apiserver_client_certificate_expiration_seconds  |  Distribution of the remaining lifetime on the certificate used to authenticate a request.| histogram |
| apiserver_storage_data_key_generation_failures_total  |  Total number of failed data encryption key(DEK) generation operations.| counter |
| apiserver_storage_data_key_generation_latencies_microseconds  |  Latencies in microseconds of data encryption key(DEK) generation operations.| histogram |
| apiserver_storage_envelope_transformation_cache_misses_total  |  Total number of cache misses while accessing key decryption key(KEK).| counter |
| cadvisor_version_info  |  A metric with a constant '1' value labeled by kernel version, OS version, docker version, cadvisor version & cadvisor revision.| gauge |
| container_cpu_cfs_periods_total  |  Number of elapsed enforcement period intervals.| counter |
| container_cpu_cfs_throttled_periods_total  |  Number of throttled period intervals.| counter |
| container_cpu_cfs_throttled_seconds_total  |  Total time duration the container has been throttled.| counter |
| container_cpu_load_average_10s  |  Value of container cpu load average over the last 10 seconds.| gauge |
| container_cpu_system_seconds_total  |  Cumulative system cpu time consumed in seconds.| counter |
| container_cpu_usage_seconds_total  |  Cumulative cpu time consumed in seconds.| counter |
| container_cpu_user_seconds_total  |  Cumulative user cpu time consumed in seconds.| counter |
| container_fs_inodes_free  |  Number of available Inodes| gauge |
| container_fs_inodes_total  |  Number of Inodes| gauge |
| container_fs_io_current  |  Number of I/Os currently in progress| gauge |
| container_fs_io_time_seconds_total  |  Cumulative count of seconds spent doing I/Os| counter |
| container_fs_io_time_weighted_seconds_total  |  Cumulative weighted I/O time in seconds| counter |
| container_fs_limit_bytes  |  Number of bytes that can be consumed by the container on this filesystem.| gauge |
| container_fs_read_seconds_total  |  Cumulative count of seconds spent reading| counter |
| container_fs_reads_bytes_total  |  Cumulative count of bytes read| counter |
| container_fs_reads_merged_total  |  Cumulative count of reads merged| counter |
| container_fs_reads_total  |  Cumulative count of reads completed| counter |
| container_fs_sector_reads_total  |  Cumulative count of sector reads completed| counter |
| container_fs_sector_writes_total  |  Cumulative count of sector writes completed| counter |
| container_fs_usage_bytes  |  Number of bytes that are consumed by the container on this filesystem.| gauge |
| container_fs_write_seconds_total  |  Cumulative count of seconds spent writing| counter |
| container_fs_writes_bytes_total  |  Cumulative count of bytes written| counter |
| container_fs_writes_merged_total  |  Cumulative count of writes merged| counter |
| container_fs_writes_total  |  Cumulative count of writes completed| counter |
| container_last_seen  |  Last time a container was seen by the exporter| gauge |
| container_memory_cache  |  Number of bytes of page cache memory.| gauge |
| container_memory_failcnt  |  Number of memory usage hits limits| counter |
| container_memory_failures_total  |  Cumulative count of memory allocation failures.| counter |
| container_memory_mapped_file  |  Size of memory mapped files in bytes.| gauge |
| container_memory_max_usage_bytes  |  Maximum memory usage recorded in bytes| gauge |
| container_memory_rss  |  Size of RSS in bytes.| gauge |
| container_memory_swap  |  Container swap usage in bytes.| gauge |
| container_memory_usage_bytes  |  Current memory usage in bytes, including all memory regardless of when it was accessed| gauge |
| container_memory_working_set_bytes  |  Current working set in bytes.| gauge |
| container_network_receive_bytes_total  |  Cumulative count of bytes received| counter |
| container_network_receive_errors_total  |  Cumulative count of errors encountered while receiving| counter |
| container_network_receive_packets_dropped_total  |  Cumulative count of packets dropped while receiving| counter |
| container_network_receive_packets_total  |  Cumulative count of packets received| counter |
| container_network_transmit_bytes_total  |  Cumulative count of bytes transmitted| counter |
| container_network_transmit_errors_total  |  Cumulative count of errors encountered while transmitting| counter |
| container_network_transmit_packets_dropped_total  |  Cumulative count of packets dropped while transmitting| counter |
| container_network_transmit_packets_total  |  Cumulative count of packets transmitted| counter |
| container_scrape_error  |  1 if there was an error while getting container metrics, 0 otherwise| gauge |
| container_spec_cpu_period  |  CPU period of the container.| gauge |
| container_spec_cpu_quota  |  CPU quota of the container.| gauge |
| container_spec_cpu_shares  |  CPU share of the container.| gauge |
| container_spec_memory_limit_bytes  |  Memory limit for the container.| gauge |
| container_spec_memory_reservation_limit_bytes  |  Memory reservation limit for the container.| gauge |
| container_spec_memory_swap_limit_bytes  |  Memory swap limit for the container.| gauge |
| container_start_time_seconds  |  Start time of the container since unix epoch in seconds.| gauge |
| container_tasks_state  |  Number of tasks in given state| gauge |
| http_request_duration_microseconds  |  The HTTP request latencies in microseconds.| summary |
| http_request_size_bytes  |  The HTTP request sizes in bytes.| summary |
| http_requests_total  |  Total number of HTTP requests made.| counter |
| http_response_size_bytes  |  The HTTP response sizes in bytes.| summary |
| kubelet_certificate_manager_client_expiration_seconds  |  Gauge of the lifetime of a certificate. The value is the date the certificate will expire in seconds since January 1, 1970 UTC.| gauge |
| kubelet_cgroup_manager_latency_microseconds  |  Latency in microseconds for cgroup manager operations. Broken down by method.| summary |
| kubelet_container_log_filesystem_used_bytes  |  Bytes used by the container's logs on the filesystem.| gauge |
| kubelet_containers_per_pod_count  |  The number of containers per pod.| summary |
| kubelet_docker_operations  |  Cumulative number of Docker operations by operation type.| counter |
| kubelet_docker_operations_errors  |  Cumulative number of Docker operation errors by operation type.| counter |
| kubelet_docker_operations_latency_microseconds  |  Latency in microseconds of Docker operations. Broken down by operation type.| summary |
| kubelet_network_plugin_operations_latency_microseconds  |  Latency in microseconds of network plugin operations. Broken down by operation type.| summary |
| kubelet_node_config_error  |  This metric is true (1) if the node is experiencing a configuration-related error, false (0) otherwise.| gauge |
| kubelet_pleg_relist_interval_microseconds  |  Interval in microseconds between relisting in PLEG.| summary |
| kubelet_pleg_relist_latency_microseconds  |  Latency in microseconds for relisting pods in PLEG.| summary |
| kubelet_pod_start_latency_microseconds  |  Latency in microseconds for a single pod to go from pending to running.| summary |
| kubelet_pod_worker_latency_microseconds  |  Latency in microseconds to sync a single pod. Broken down by operation type: create, update, or sync| summary |
| kubelet_pod_worker_start_latency_microseconds  |  Latency in microseconds from seeing a pod to starting a worker.| summary |
| kubelet_running_container_count  |  Number of containers currently running| gauge |
| kubelet_running_pod_count  |  Number of pods currently running| gauge |
| kubelet_runtime_operations  |  Cumulative number of runtime operations by operation type.| counter |
| kubelet_runtime_operations_errors  |  Cumulative number of runtime operation errors by operation type.| counter |
| kubelet_runtime_operations_latency_microseconds  |  Latency in microseconds of runtime operations. Broken down by operation type.| summary |
| kubernetes_build_info  |  A metric with a constant '1' value labeled by major, minor, git version, git commit, git tree state, build date, Go version, and compiler from which Kubernetes was built, and platform on which it is running.| gauge |
| machine_cpu_cores  |  Number of CPU cores on the machine.| gauge |
| machine_memory_bytes  |  Amount of memory installed on the machine.| gauge |
| process_cpu_seconds_total  |  Total user and system CPU time spent in seconds.| counter |
| process_max_fds  |  Maximum number of open file descriptors.| gauge |
| process_open_fds  |  Number of open file descriptors.| gauge |
| process_resident_memory_bytes  |  Resident memory size in bytes.| gauge |
| process_start_time_seconds  |  Start time of the process since unix epoch in seconds.| gauge |
| process_virtual_memory_bytes  |  Virtual memory size in bytes.| gauge |
| rest_client_request_latency_seconds  |  Request latency in seconds. Broken down by verb and URL.| histogram |
| rest_client_requests_total  |  Number of HTTP requests, partitioned by status code, method, and host.| counter |
| storage_operation_duration_seconds  |  Storage operation duration| histogram |
| volume_manager_total_volumes  |  Number of volumes in Volume Manager| gauge |
