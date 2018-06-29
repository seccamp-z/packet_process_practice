
# Packet filtering

Filter the packets according following filter table
and save filtered packets in the other pcap-file.
Receive packets from the ``in.pcap``.

```
src                  dst            ip-proto      outputfile
-------------------------------------------------------------
133.25.167.227:any   dpdk.ninja:22  tcp           rule1.pcap
any:any              dpdk.ninja:22  tcp           rule2.pcap
any:any              dpdk.ninja:80  tcp           rule3.pcap
```

IF you feel this question is too easy, generalize this filter.
and implement ip-range filtering. (161.200.238.18/28)

