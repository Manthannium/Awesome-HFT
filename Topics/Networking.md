# Networking Topics

### **Routing**
- Distance Vector Routing (e.g., RIP)
- Link State Routing (e.g., OSPF)
- Path Vector Routing (e.g., BGP)
- Dijkstra’s Algorithm
- Bellman-Ford Algorithm
- Static vs. Dynamic Routing
- Hierarchical routing
- Route flapping and route dampening (BGP)
- Software-defined routing
- What is the difference between Distance Vector and Link State routing?
- What is the “count to infinity” problem? How is it solved?
- How does BGP prevent routing loops?

### **Congestion Control Algorithms**
- TCP Congestion Control: Slow Start, Congestion Avoidance, Fast Retransmit, Fast Recovery
- Additive Increase/Multiplicative Decrease (AIMD)
- ECN (Explicit Congestion Notification)
- TCP Reno, Tahoe, Cubic
- BBR (Bottleneck Bandwidth and Round-trip propagation time)
- Congestion control in RDMA/InfiniBand (low-latency networks)
- Explain TCP congestion control phases.
- What’s the difference between TCP Reno and TCP Cubic?
- How does ECN work?

### **IP Addressing & Subnetting**
- IP classes (A, B, C, D, E)
- CIDR (Classless Inter-Domain Routing)
- Subnet masks
- Calculating usable hosts in a subnet
- Private vs Public IP ranges
- Supernetting
- Subnetting for performance isolation
- Convert a subnet mask to CIDR notation.
- How many hosts can 255.255.255.240 support?
- What's the purpose of subnetting?

### **IPv4 and IPv6 Protocols**
- IPv4 Header and fields
- IPv6 Header, addressing format, compression
- Stateless and Stateful address configuration
- IPv6 advantages (simplified header, larger space)
- Dual stack vs Tunneling IPv6 over IPv4
- IPv6 flow labels
- Key differences between IPv4 and IPv6?
- Why is NAT not needed in IPv6?
- How does IPv6 handle fragmentation?

### **ICMP (Internet Control Message Protocol)**
- ICMP Echo (ping), Destination Unreachable, TTL Exceeded
- ICMPv6
- Use of ICMP in traceroute
- What happens when you ping an unreachable host?
- How does traceroute use ICMP?

### **Fragmentation**
- MTU (Maximum Transmission Unit)
- IP fragmentation and reassembly
- Flags: DF (Don't Fragment), MF (More Fragments)
- What causes IP fragmentation?
- How does fragmentation affect performance?
- How is fragmentation handled in IPv6?

### **Tunneling**
- VPNs and IPsec
- GRE (Generic Routing Encapsulation)
- Tunneling IPv6 over IPv4
- MPLS (Multiprotocol Label Switching)
- What is IP tunneling and how is it used?
- What’s the role of tunneling in VPNs?
- Explain how MPLS works.

### **Subnet**
- Subnetting calculation
- Network ID, Broadcast Address
- Subnetting in enterprise vs data centers
- How do you split a network into multiple subnets?
- How is subnetting used for security?

### **Gateway and Router**
- Default Gateway role
- Router’s job in packet forwarding
- Static vs Dynamic routing on routers
- What’s the difference between a gateway and a router?
- What happens when a packet doesn’t match any route?

### **Count to Infinity Problem**
- Problem in distance vector protocols
- Hop count increase during failures
- Split Horizon, Poison Reverse
- Explain the count to infinity problem.
- How do distance vector protocols mitigate this?
