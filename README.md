Built a simple IP router in user space, that provide libpcap and raw sockets interface. 

In order to build an IP router, we captured packets sent to the router, and determined the next hop and then forwarded the packet to that next hop. 

Able to achieve a throughput of 784 Mbps on a 1Gbps channel with 10 ms delay.

The router was capable for sending ICMP replies and also generate ICMP time exceeded messages for TTL =1 for working of traceroute.
