| metric  |  description | type |
|  --- | --- | --- |
| node_arp_entries  |  ARP entries by device | gauge |
| node_boot_time_seconds  |  Node boot time, in unixtime | gauge |
| node_context_switches_total  |  Total number of context switches | counter |
| node_cpu_guest_seconds_total  |  Seconds the cpus spent in guests (VMs) for each mode | counter |
| node_cpu_seconds_total  |  Seconds the cpus spent in each mode. | counter |
| node_disk_io_now  |  The number of I/Os currently in progress. | gauge |
| node_disk_io_time_seconds_total  |  Total seconds spent doing I/Os. | counter |
| node_disk_io_time_weighted_seconds_total  |  The weighted # of seconds spent doing I/Os. | counter |
| node_disk_read_bytes_total  |  The total number of bytes read successfully. | counter |
| node_disk_read_time_seconds_total  |  The total number of seconds spent by all reads. | counter |
| node_disk_reads_completed_total  |  The total number of reads completed successfully. | counter |
| node_disk_reads_merged_total  |  The total number of reads merged. | counter |
| node_disk_write_time_seconds_total  |  This is the total number of seconds spent by all writes. | counter |
| node_disk_writes_completed_total  |  The total number of writes completed successfully. | counter |
| node_disk_writes_merged_total  |  The number of writes merged. | counter |
| node_disk_written_bytes_total  |  The total number of bytes written successfully. | counter |
| node_entropy_available_bits  |  Bits of available entropy. | gauge |
| node_exporter_build_info  |  A metric with a constant '1' value labeled by version, revision, branch, and goversion from which node_exporter was built. | gauge |
| node_filefd_allocated  |  File descriptor statistics: allocated. | gauge |
| node_filefd_maximum  |  File descriptor statistics: maximum. | gauge |
| node_filesystem_avail_bytes  |  Filesystem space available to non-root users in bytes. | gauge |
| node_filesystem_device_error  |  Whether an error occurred while getting statistics for the given device. | gauge |
| node_filesystem_files  |  Filesystem total file nodes. | gauge |
| node_filesystem_files_free  |  Filesystem total free file nodes. | gauge |
| node_filesystem_free_bytes  |  Filesystem free space in bytes. | gauge |
| node_filesystem_readonly  |  Filesystem read-only status. | gauge |
| node_filesystem_size_bytes  |  Filesystem size in bytes. | gauge |
| node_forks_total  |  Total number of forks. | counter |
| node_intr_total  |  Total number of interrupts serviced. | counter |
| node_load1  |  1m load average. | gauge |
| node_load15  |  15m load average. | gauge |
| node_load5  |  5m load average. | gauge |
| node_memory_Active_anon_bytes  |  Memory information field Active_anon_bytes. | gauge |
| node_memory_Active_bytes  |  Memory information field Active_bytes. | gauge |
| node_memory_Active_file_bytes  |  Memory information field Active_file_bytes. | gauge |
| node_memory_AnonHugePages_bytes  |  Memory information field AnonHugePages_bytes. | gauge |
| node_memory_AnonPages_bytes  |  Memory information field AnonPages_bytes. | gauge |
| node_memory_Bounce_bytes  |  Memory information field Bounce_bytes. | gauge |
| node_memory_Buffers_bytes  |  Memory information field Buffers_bytes. | gauge |
| node_memory_Cached_bytes  |  Memory information field Cached_bytes. | gauge |
| node_memory_CmaFree_bytes  |  Memory information field CmaFree_bytes. | gauge |
| node_memory_CmaTotal_bytes  |  Memory information field CmaTotal_bytes. | gauge |
| node_memory_CommitLimit_bytes  |  Memory information field CommitLimit_bytes. | gauge |
| node_memory_Committed_AS_bytes  |  Memory information field Committed_AS_bytes. | gauge |
| node_memory_DirectMap1G_bytes  |  Memory information field DirectMap1G_bytes. | gauge |
| node_memory_DirectMap2M_bytes  |  Memory information field DirectMap2M_bytes. | gauge |
| node_memory_DirectMap4k_bytes  |  Memory information field DirectMap4k_bytes. | gauge |
| node_memory_Dirty_bytes  |  Memory information field Dirty_bytes. | gauge |
| node_memory_HardwareCorrupted_bytes  |  Memory information field HardwareCorrupted_bytes. | gauge |
| node_memory_HugePages_Free  |  Memory information field HugePages_Free. | gauge |
| node_memory_HugePages_Rsvd  |  Memory information field HugePages_Rsvd. | gauge |
| node_memory_HugePages_Surp  |  Memory information field HugePages_Surp. | gauge |
| node_memory_HugePages_Total  |  Memory information field HugePages_Total. | gauge |
| node_memory_Hugepagesize_bytes  |  Memory information field Hugepagesize_bytes. | gauge |
| node_memory_Inactive_anon_bytes  |  Memory information field Inactive_anon_bytes. | gauge |
| node_memory_Inactive_bytes  |  Memory information field Inactive_bytes. | gauge |
| node_memory_Inactive_file_bytes  |  Memory information field Inactive_file_bytes. | gauge |
| node_memory_KernelStack_bytes  |  Memory information field KernelStack_bytes. | gauge |
| node_memory_Mapped_bytes  |  Memory information field Mapped_bytes. | gauge |
| node_memory_MemAvailable_bytes  |  Memory information field MemAvailable_bytes. | gauge |
| node_memory_MemFree_bytes  |  Memory information field MemFree_bytes. | gauge |
| node_memory_MemTotal_bytes  |  Memory information field MemTotal_bytes. | gauge |
| node_memory_Mlocked_bytes  |  Memory information field Mlocked_bytes. | gauge |
| node_memory_NFS_Unstable_bytes  |  Memory information field NFS_Unstable_bytes. | gauge |
| node_memory_PageTables_bytes  |  Memory information field PageTables_bytes. | gauge |
| node_memory_SReclaimable_bytes  |  Memory information field SReclaimable_bytes. | gauge |
| node_memory_SUnreclaim_bytes  |  Memory information field SUnreclaim_bytes. | gauge |
| node_memory_Shmem_bytes  |  Memory information field Shmem_bytes. | gauge |
| node_memory_Slab_bytes  |  Memory information field Slab_bytes. | gauge |
| node_memory_SwapCached_bytes  |  Memory information field SwapCached_bytes. | gauge |
| node_memory_SwapFree_bytes  |  Memory information field SwapFree_bytes. | gauge |
| node_memory_SwapTotal_bytes  |  Memory information field SwapTotal_bytes. | gauge |
| node_memory_Unevictable_bytes  |  Memory information field Unevictable_bytes. | gauge |
| node_memory_VmallocChunk_bytes  |  Memory information field VmallocChunk_bytes. | gauge |
| node_memory_VmallocTotal_bytes  |  Memory information field VmallocTotal_bytes. | gauge |
| node_memory_VmallocUsed_bytes  |  Memory information field VmallocUsed_bytes. | gauge |
| node_memory_WritebackTmp_bytes  |  Memory information field WritebackTmp_bytes. | gauge |
| node_memory_Writeback_bytes  |  Memory information field Writeback_bytes. | gauge |
| node_netstat_Icmp6_InErrors  |  Statistic Icmp6InErrors. | untyped |
| node_netstat_Icmp6_InMsgs  |  Statistic Icmp6InMsgs. | untyped |
| node_netstat_Icmp6_OutMsgs  |  Statistic Icmp6OutMsgs. | untyped |
| node_netstat_Icmp_InErrors  |  Statistic IcmpInErrors. | untyped |
| node_netstat_Icmp_InMsgs  |  Statistic IcmpInMsgs. | untyped |
| node_netstat_Icmp_OutMsgs  |  Statistic IcmpOutMsgs. | untyped |
| node_netstat_Ip6_InOctets  |  Statistic Ip6InOctets. | untyped |
| node_netstat_Ip6_OutOctets  |  Statistic Ip6OutOctets. | untyped |
| node_netstat_IpExt_InOctets  |  Statistic IpExtInOctets. | untyped |
| node_netstat_IpExt_OutOctets  |  Statistic IpExtOutOctets. | untyped |
| node_netstat_Ip_Forwarding  |  Statistic IpForwarding. | untyped |
| node_netstat_TcpExt_ListenDrops  |  Statistic TcpExtListenDrops. | untyped |
| node_netstat_TcpExt_ListenOverflows  |  Statistic TcpExtListenOverflows. | untyped |
| node_netstat_TcpExt_SyncookiesFailed  |  Statistic TcpExtSyncookiesFailed. | untyped |
| node_netstat_TcpExt_SyncookiesRecv  |  Statistic TcpExtSyncookiesRecv. | untyped |
| node_netstat_TcpExt_SyncookiesSent  |  Statistic TcpExtSyncookiesSent. | untyped |
| node_netstat_TcpExt_TCPSynRetrans  |  Statistic TcpExtTCPSynRetrans. | untyped |
| node_netstat_Tcp_ActiveOpens  |  Statistic TcpActiveOpens. | untyped |
| node_netstat_Tcp_CurrEstab  |  Statistic TcpCurrEstab. | untyped |
| node_netstat_Tcp_InErrs  |  Statistic TcpInErrs. | untyped |
| node_netstat_Tcp_InSegs  |  Statistic TcpInSegs. | untyped |
| node_netstat_Tcp_OutSegs  |  Statistic TcpOutSegs. | untyped |
| node_netstat_Tcp_PassiveOpens  |  Statistic TcpPassiveOpens. | untyped |
| node_netstat_Tcp_RetransSegs  |  Statistic TcpRetransSegs. | untyped |
| node_netstat_Udp6_InDatagrams  |  Statistic Udp6InDatagrams. | untyped |
| node_netstat_Udp6_InErrors  |  Statistic Udp6InErrors. | untyped |
| node_netstat_Udp6_NoPorts  |  Statistic Udp6NoPorts. | untyped |
| node_netstat_Udp6_OutDatagrams  |  Statistic Udp6OutDatagrams. | untyped |
| node_netstat_UdpLite6_InErrors  |  Statistic UdpLite6InErrors. | untyped |
| node_netstat_UdpLite_InErrors  |  Statistic UdpLiteInErrors. | untyped |
| node_netstat_Udp_InDatagrams  |  Statistic UdpInDatagrams. | untyped |
| node_netstat_Udp_InErrors  |  Statistic UdpInErrors. | untyped |
| node_netstat_Udp_NoPorts  |  Statistic UdpNoPorts. | untyped |
| node_netstat_Udp_OutDatagrams  |  Statistic UdpOutDatagrams. | untyped |
| node_network_address_assign_type  |  address_assign_type value of /sys/class/net/<iface>. | gauge |
| node_network_carrier  |  carrier value of /sys/class/net/<iface>. | gauge |
| node_network_carrier_changes_total  |  carrier_changes_total value of /sys/class/net/<iface>. | counter |
| node_network_device_id  |  device_id value of /sys/class/net/<iface>. | gauge |
| node_network_dormant  |  dormant value of /sys/class/net/<iface>. | gauge |
| node_network_flags  |  flags value of /sys/class/net/<iface>. | gauge |
| node_network_iface_id  |  iface_id value of /sys/class/net/<iface>. | gauge |
| node_network_iface_link  |  iface_link value of /sys/class/net/<iface>. | gauge |
| node_network_iface_link_mode  |  iface_link_mode value of /sys/class/net/<iface>. | gauge |
| node_network_info  |  Non-numeric data from /sys/class/net/<iface>, value is always 1. | gauge |
| node_network_mtu_bytes  |  mtu_bytes value of /sys/class/net/<iface>. | gauge |
| node_network_net_dev_group  |  net_dev_group value of /sys/class/net/<iface>. | gauge |
| node_network_protocol_type  |  protocol_type value of /sys/class/net/<iface>. | gauge |
| node_network_receive_bytes_total  |  Network device statistic receive_bytes. | counter |
| node_network_receive_compressed_total  |  Network device statistic receive_compressed. | counter |
| node_network_receive_drop_total  |  Network device statistic receive_drop. | counter |
| node_network_receive_errs_total  |  Network device statistic receive_errs. | counter |
| node_network_receive_fifo_total  |  Network device statistic receive_fifo. | counter |
| node_network_receive_frame_total  |  Network device statistic receive_frame. | counter |
| node_network_receive_multicast_total  |  Network device statistic receive_multicast. | counter |
| node_network_receive_packets_total  |  Network device statistic receive_packets. | counter |
| node_network_speed_bytes  |  speed_bytes value of /sys/class/net/<iface>. | gauge |
| node_network_transmit_bytes_total  |  Network device statistic transmit_bytes. | counter |
| node_network_transmit_carrier_total  |  Network device statistic transmit_carrier. | counter |
| node_network_transmit_colls_total  |  Network device statistic transmit_colls. | counter |
| node_network_transmit_compressed_total  |  Network device statistic transmit_compressed. | counter |
| node_network_transmit_drop_total  |  Network device statistic transmit_drop. | counter |
| node_network_transmit_errs_total  |  Network device statistic transmit_errs. | counter |
| node_network_transmit_fifo_total  |  Network device statistic transmit_fifo. | counter |
| node_network_transmit_packets_total  |  Network device statistic transmit_packets. | counter |
| node_network_transmit_queue_length  |  transmit_queue_length value of /sys/class/net/<iface>. | gauge |
| node_network_up  |  Value is 1 if operstate is 'up', 0 otherwise. | gauge |
| node_nf_conntrack_entries  |  Number of currently allocated flow entries for connection tracking. | gauge |
| node_nf_conntrack_entries_limit  |  Maximum size of connection tracking table. | gauge |
| node_procs_blocked  |  Number of processes blocked waiting for I/O to complete. | gauge |
| node_procs_running  |  Number of processes in runnable state. | gauge |
| node_scrape_collector_duration_seconds  |  node_exporter: Duration of a collector scrape. | gauge |
| node_scrape_collector_success  |  node_exporter: Whether a collector succeeded. | gauge |
| node_sockstat_FRAG_inuse  |  Number of FRAG sockets in state inuse. | gauge |
| node_sockstat_FRAG_memory  |  Number of FRAG sockets in state memory. | gauge |
| node_sockstat_RAW_inuse  |  Number of RAW sockets in state inuse. | gauge |
| node_sockstat_TCP_alloc  |  Number of TCP sockets in state alloc. | gauge |
| node_sockstat_TCP_inuse  |  Number of TCP sockets in state inuse. | gauge |
| node_sockstat_TCP_mem  |  Number of TCP sockets in state mem. | gauge |
| node_sockstat_TCP_mem_bytes  |  Number of TCP sockets in state mem_bytes. | gauge |
| node_sockstat_TCP_orphan  |  Number of TCP sockets in state orphan. | gauge |
| node_sockstat_TCP_tw  |  Number of TCP sockets in state tw. | gauge |
| node_sockstat_UDPLITE_inuse  |  Number of UDPLITE sockets in state inuse. | gauge |
| node_sockstat_UDP_inuse  |  Number of UDP sockets in state inuse. | gauge |
| node_sockstat_UDP_mem  |  Number of UDP sockets in state mem. | gauge |
| node_sockstat_UDP_mem_bytes  |  Number of UDP sockets in state mem_bytes. | gauge |
| node_sockstat_sockets_used  |  Number of sockets sockets in state used. | gauge |
| node_textfile_scrape_error  |  1 if there was an error opening or reading a file, 0 otherwise | gauge |
| node_time_seconds  |  System time in seconds since epoch (1970). | gauge |
| node_timex_estimated_error_seconds  |  Estimated error in seconds. | gauge |
| node_timex_frequency_adjustment_ratio  |  Local clock frequency adjustment. | gauge |
| node_timex_loop_time_constant  |  Phase-locked loop time constant. | gauge |
| node_timex_maxerror_seconds  |  Maximum error in seconds. | gauge |
| node_timex_offset_seconds  |  Time offset in between local system and reference clock. | gauge |
| node_timex_pps_calibration_total  |  Pulse per second count of calibration intervals. | counter |
| node_timex_pps_error_total  |  Pulse per second count of calibration errors. | counter |
| node_timex_pps_frequency_hertz  |  Pulse per second frequency. | gauge |
| node_timex_pps_jitter_seconds  |  Pulse per second jitter. | gauge |
| node_timex_pps_jitter_total  |  Pulse per second count of jitter limit exceeded events. | counter |
| node_timex_pps_shift_seconds  |  Pulse per second interval duration. | gauge |
| node_timex_pps_stability_exceeded_total  |  Pulse per second count of stability limit exceeded events. | counter |
| node_timex_pps_stability_hertz  |  Pulse per second stability, average of recent frequency changes. | gauge |
| node_timex_status  |  Value of the status array bits. | gauge |
| node_timex_sync_status  |  Is clock synchronized to a reliable server (1 = yes, 0 = no). | gauge |
| node_timex_tai_offset_seconds  |  International Atomic Time (TAI) offset. | gauge |
| node_timex_tick_seconds  |  Seconds between clock ticks. | gauge |
| node_uname_info  |  Labeled system information as provided by the uname system call. | gauge |
| node_vmstat_pgfault  |  /proc/vmstat information field pgfault. | untyped |
| node_vmstat_pgmajfault  |  /proc/vmstat information field pgmajfault. | untyped |
| node_vmstat_pgpgin  |  /proc/vmstat information field pgpgin. | untyped |
| node_vmstat_pgpgout  |  /proc/vmstat information field pgpgout. | untyped |
| node_vmstat_pswpin  |  /proc/vmstat information field pswpin. | untyped |
| node_vmstat_pswpout  |  /proc/vmstat information field pswpout. | untyped |
| node_xfs_allocation_btree_compares_total  |  Number of allocation B-tree compares for a filesystem. | counter |
| node_xfs_allocation_btree_lookups_total  |  Number of allocation B-tree lookups for a filesystem. | counter |
| node_xfs_allocation_btree_records_deleted_total  |  Number of allocation B-tree records deleted for a filesystem. | counter |
| node_xfs_allocation_btree_records_inserted_total  |  Number of allocation B-tree records inserted for a filesystem. | counter |
| node_xfs_block_map_btree_compares_total  |  Number of block map B-tree compares for a filesystem. | counter |
| node_xfs_block_map_btree_lookups_total  |  Number of block map B-tree lookups for a filesystem. | counter |
| node_xfs_block_map_btree_records_deleted_total  |  Number of block map B-tree records deleted for a filesystem. | counter |
| node_xfs_block_map_btree_records_inserted_total  |  Number of block map B-tree records inserted for a filesystem. | counter |
| node_xfs_block_mapping_extent_list_compares_total  |  Number of extent list compares for a filesystem. | counter |
| node_xfs_block_mapping_extent_list_deletions_total  |  Number of extent list deletions for a filesystem. | counter |
| node_xfs_block_mapping_extent_list_insertions_total  |  Number of extent list insertions for a filesystem. | counter |
| node_xfs_block_mapping_extent_list_lookups_total  |  Number of extent list lookups for a filesystem. | counter |
| node_xfs_block_mapping_reads_total  |  Number of block map for read operations for a filesystem. | counter |
| node_xfs_block_mapping_unmaps_total  |  Number of block unmaps (deletes) for a filesystem. | counter |
| node_xfs_block_mapping_writes_total  |  Number of block map for write operations for a filesystem. | counter |
| node_xfs_extent_allocation_blocks_allocated_total  |  Number of blocks allocated for a filesystem. | counter |
| node_xfs_extent_allocation_blocks_freed_total  |  Number of blocks freed for a filesystem. | counter |
| node_xfs_extent_allocation_extents_allocated_total  |  Number of extents allocated for a filesystem. | counter |
| node_xfs_extent_allocation_extents_freed_total  |  Number of extents freed for a filesystem. | counter |
| process_cpu_seconds_total  |  Total user and system CPU time spent in seconds. | counter |
| process_max_fds  |  Maximum number of open file descriptors. | gauge |
| process_open_fds  |  Number of open file descriptors. | gauge |
| process_resident_memory_bytes  |  Resident memory size in bytes. | gauge |
| process_start_time_seconds  |  Start time of the process since unix epoch in seconds. | gauge |
| process_virtual_memory_bytes  |  Virtual memory size in bytes. | gauge |
| process_virtual_memory_max_bytes  |  Maximum amount of virtual memory available in bytes. | gauge |
| promhttp_metric_handler_requests_in_flight  |  Current number of scrapes being served. | gauge |
| promhttp_metric_handler_requests_total  |  Total number of scrapes by HTTP status code. | counter |
