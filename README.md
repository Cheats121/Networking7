# Networking7
BGP + Redundancy
--------------------
# Lab 7: VRRP & BGP

### Overview
Implemented VRRP for gateway redundancy and BGP for protocol redistribution between two routing domains.

### Topology
- **Topology A**: EIGRP + VRRP  
- **Topology B**: OSPF + VRRP  
- Single BGP router interconnecting A & B.

### Tasks & Results
1. **VRRP Setup**  
   - Assigned virtual IP 192.168.1.4; demonstrated master→backup failover.

2. **BGP Redistribution**  
   - Configured BGP neighbours; redistributed IGP routes across domains.  
   - Verified full route visibility on R6 (topology B) and R8 (topology A).

### Lessons Learned
- VRRP election process and timers.
- BGP neighbour relationships and route redistribution.
