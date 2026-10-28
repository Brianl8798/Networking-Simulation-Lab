# Networking Simulation Lab : Enterprise Topologies with Cisco

<p align="center">
  Designed and troubleshot enterprise network topologies using Cisco routing, switching and security best practices.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cisco-1BA0D7?logo=cisco&logoColor=white" alt="Cisco">
  <img src="https://img.shields.io/badge/CCNA-Aligned-0066CC" alt="CCNA Aligned">
  <img src="https://img.shields.io/badge/Wireshark-1679A7?logo=wireshark&logoColor=white" alt="Wireshark">
  <img src="https://img.shields.io/badge/Duration-2_weeks-lightgrey" alt="2 weeks">
</p>

> [!TIP]
> **Results at a glance** — jump to [Key results](#key-results).
>
> - ⚡ OSPF convergence time cut by **30%** through timer tuning
> - 🧱 Broadcast domains isolated with **10+ VLANs**
> - 🔒 Unauthorized access blocked with **ACLs**

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Core components](#core-components)
- [Configuration examples](#configuration-examples)
- [Key results](#key-results)
- [Skills demonstrated](#skills-demonstrated)
- [Lessons learned](#lessons-learned)
- [Credits](#credits)

## Introduction

A **2-week intensive lab** simulating enterprise networks with routing protocols and security controls, built and tested in **Cisco Packet Tracer / GNS3** and verified with **Wireshark**.

## Features

- Multi-protocol routing with **OSPF and EIGRP**, including route redistribution
- **10+ VLANs** with VTP and STP optimization
- Layer 2 security with **Port Security** and **DHCP Snooping**
- Traffic filtering with **ACLs**
- Packet-level verification with **Wireshark**

## Core components

| Technology | Implementation |
| --- | --- |
| **Routing** | OSPF, EIGRP with route redistribution |
| **Switching** | VLANs (10+), VTP, STP optimization |
| **Security** | ACLs, Port Security, DHCP Snooping |

## Configuration examples

**Blocking Telnet with an ACL**

```
access-list 101 deny tcp any any eq 23
access-list 101 permit ip any any
```

## Key results

- Optimized OSPF convergence time by **30%** through timer tuning
- Isolated broadcast domains with **10+ VLANs**
- Blocked **unauthorized access via ACLs** (e.g. `deny tcp any any eq 23`)

## Skills demonstrated

`Routing Protocols` · `VLANs` · `ACLs` · `Troubleshooting` · `CCNA Concepts`

## Lessons learned

> STP tuning prevents switching loops in complex topologies.

> Route redistribution requires careful metric conversion.

## Credits

- Brian Lam — [GitHub](https://github.com/Brianl8798) · [LinkedIn](https://www.linkedin.com/in/brian-lam-282176172/)
