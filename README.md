# 🌐 Networking Simulation Lab

*Designed and troubleshot enterprise network topologies using Cisco protocols and security best practices*

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?logo=cisco&logoColor=white)
![Network](https://img.shields.io/badge/CCNA_Aligned-0066CC?logo=network&logoColor=white)

## 📌 Overview
- **Goal**: Simulate enterprise networks with routing protocols and security controls
- **Tools**: Cisco Packet Tracer / GNS3, Wireshark
- **Duration**: 2-week intensive lab

## 🛠️ Technical Implementation
### Core Components
| **Technology** | **Implementation** |
|---------------|--------------------|
| **Routing** | OSPF, EIGRP with route redistribution |
| **Switching** | VLANs (10+), VTP, STP optimization |
| **Security** | ACLs, Port Security, DHCP Snooping |

### Sample Configuration
```cisco
! OSPF Configuration
router ospf 1
 network 192.168.1.0 0.0.0.255 area 0
!
! VLAN Creation
vlan 10
 name Engineering
!
! Port Security
interface Gig0/1
 switchport port-security
 switchport port-security maximum 2
```

 Key Results
 
Optimized OSPF convergence time by 30% through timer tuning

Isolated broadcast domains with 10+ VLANs

Blocked unauthorized access via ACLs (e.g., deny tcp any any eq 23)

🎯 Skills Demonstrated

Routing Protocols - VLANs - ACLs - Troubleshooting - CCNA Concepts

💡 Lessons Learned

"STP tuning prevents switching loops in complex topologies"

"Route redistribution requires careful metric conversion"
