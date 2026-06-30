# OSPF Multi-Router Network

## Overview

This project demonstrates the configuration of Open Shortest Path First (OSPF) dynamic routing in a multi-router topology using Cisco Packet Tracer.

The network consists of five routers connected through serial links with two LANs located at opposite ends of the network.

---

## Features

- OSPF Dynamic Routing
- Multi-Router Topology
- Serial WAN Links
- Route Advertisement
- OSPF Neighbor Formation
- End-to-End Connectivity
- Cisco Packet Tracer Implementation

---

## Network Topology

![Topology](images/topology.png)

---

## Network Diagram

```
PC1 ---- Switch ---- Router3
                    |
                 Serial
                    |
                 Router1
                    |
                 Router0
                    |
                 Router2
                    |
                 Serial
                    |
PC3 ---- Switch ---- Router4
```

---

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- OSPF Routing Protocol
- Serial Interfaces
- Ethernet Networking

---

## OSPF Configuration

Each router was configured with:

```
router ospf 1
network <network> <wildcard-mask> area 0
```

---

## Verification Commands

```
show ip route
show ip ospf neighbor
show ip protocols
```

---

## Routing Table

![Router0](images/router0-route.png)

![Router1](images/router1-route.png)

![Router2](images/router2-route.png)

![Router3](images/router3-route.png)

![Router4](images/router4-route.png)

---

## OSPF Neighbor Verification

![Neighbors](images/ospf-neighbors.png)

---

## Connectivity Test

The project successfully demonstrated end-to-end communication across the OSPF network.

![Ping](images/ping-test.png)

---

## Project Files

- Cisco Packet Tracer (.pkt)
- OSPF Configuration
- Routing Tables
- Verification Screenshots

---

## Author

**Asawari Kale**

Computer Engineering Student

Mumbai University

Interested in Networking & Cybersecurity
