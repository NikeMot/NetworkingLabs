# 24-Lab Networking, Cybersecurity, Automation, Cloud Administration, and AI Curriculum

## Curriculum rule

This lab series is now a 24-lab programme.

The first 16 labs are based on `Computer Networks`, Sixth Edition, Global Edition by Tanenbaum, Feamster, and Wetherall. The book has eight main chapters before the bibliography, so the curriculum uses the rule:

```text
1 chapter = 2 labs
8 chapters = 16 labs
```

After the 16 chapter labs, there are 7 drill labs and 1 final capstone lab.

```text
16 chapter labs + 7 drill labs + 1 capstone = 24 labs total
```

## Target job alignment

The curriculum is designed to build portfolio evidence for:

- advanced network troubleshooting and diagnostics
- enterprise LAN, WAN, and Wi-Fi architecture
- network performance and availability management
- network security and firewall policy reasoning, including Cisco, Juniper, and Palo Alto style concepts
- network automation, validation, and source-of-truth thinking
- observability tooling, management tooling, and CMDB strategy
- cost optimisation and solution design
- consulting-quality documentation and cross-team communication

## Source hierarchy

| Role | Source |
| --- | --- |
| Primary chapter base | `Computer Networks` |
| How to perform operational tasks | `The Practice of System and Network Administration` |
| How to perform cloud/admin tasks | `The Practice of Cloud Administration` |
| Socket programming support | `Beej's Guide to Network Programming` |
| Automation support | `Network Programmability and Automation` |
| Application-layer and Internet model support | `Computer Networking: A Top-Down Approach` |
| Security support | `Bulletproof TLS and PKI` and cybersecurity books from Drive |
| AI support | `AI Engineering`, `AI Systems Performance Engineering`, `Hands-On Large Language Models`, and `Prompt Engineering for LLMs` |

## Cybersecurity track integration

A separate detailed cybersecurity track was not provided by the user. The current cybersecurity track is therefore integrated from the user's requirement to include cybersecurity with networking, plus the security sources in Drive.

The integrated cybersecurity track covers:

- security principles and the CIA triad
- threat modelling and trust boundaries
- segmentation and least privilege
- NAT, firewall rules, and enterprise firewall policy reasoning
- Cisco, Juniper, and Palo Alto style firewall concepts
- TLS, certificates, and PKI
- authentication and authorisation concepts
- secure configuration and controlled change
- packet and log evidence
- network security monitoring
- incident triage and defensive documentation

Cybersecurity is concentrated in Labs 8, 10, 15, 16, 21, and 24, but security considerations should appear in every lab.

## Operating method used in every lab

Every lab must be performed as operational engineering work:

- define expected state
- perform a controlled implementation or troubleshooting task
- collect command, packet, log, configuration, or script evidence
- validate the final state
- document issues encountered and fixes applied
- consider security, reliability, monitoring, rollback, cost, and cloud/admin implications
- use AI only where helpful, and validate AI output against primary evidence

## 24-lab map

| Lab | Base chapter / type | Lab title | Integrated supporting content |
| ---: | --- | --- | --- |
| 1 | Chapter 1 - Introduction | Network models and packet flow baseline | OSI/TCP-IP, Linux tools, operational evidence, AI-assisted explanation validation |
| 2 | Chapter 1 - Introduction | Protocol layering, services, tooling landscape, and troubleshooting method | System/network admin method, service dependency mapping, CMDB/source-of-truth thinking, runbook documentation |
| 3 | Chapter 2 - Physical Layer | Media, bandwidth, latency, WAN access, and measurement | Cloud connectivity, Wi-Fi/fibre/copper concepts, monitoring and performance baselines |
| 4 | Chapter 2 - Physical Layer | Loss, throughput, availability, and physical-layer fault isolation | Measurement, troubleshooting records, cost/performance trade-offs, AI-assisted metric interpretation |
| 5 | Chapter 3 - Data Link Layer | Frames, MAC addresses, ARP, and local delivery | Packet capture, Linux inspection, evidence handling, secure local network assumptions |
| 6 | Chapter 3 - Data Link Layer | Error handling, flow control, and link reliability | Reliability thinking, validation, monitoring, operational notes |
| 7 | Chapter 4 - MAC Sublayer | Ethernet switching, bridges, and VLAN segmentation | Switching, VLANs, segmentation, access control, production design notes |
| 8 | Chapter 4 - MAC Sublayer | Wireless LANs, shared media, and secure LAN design | Wi-Fi concepts, LAN security, trust boundaries, monitoring, documentation |
| 9 | Chapter 5 - Network Layer | IP addressing, subnetting, forwarding, and routing | Route tables, Linux networking, cloud routing, controlled change method |
| 10 | Chapter 5 - Network Layer | NAT, firewalls, path troubleshooting, and cloud network design | NAT/PAT, ACLs, NSGs/security rules, Palo Alto/Cisco/Juniper style policy reasoning, rollback thinking |
| 11 | Chapter 6 - Transport Layer | TCP handshake, connection state, reliability, and congestion | `ss`, packet capture, service health, monitoring, incident evidence |
| 12 | Chapter 6 - Transport Layer | UDP, TCP sockets, ports, and service exposure | Beej socket programming, Python tools, firewall validation, safe lab-only exposure |
| 13 | Chapter 7 - Application Layer | DNS, HTTP, TLS, and application dependency mapping | Top-down application model, TLS/PKI, service health checks, runbooks |
| 14 | Chapter 7 - Application Layer | Application troubleshooting with logs, proxies, APIs, and observability | HTTP tools, reverse proxy concepts, API checks, AI-assisted log summarisation, tooling gaps |
| 15 | Chapter 8 - Network Security | Security principles, TLS/PKI, identity, least privilege, and firewall policy | Bulletproof TLS/PKI, authentication, encryption, secure configuration, enterprise firewall policy reasoning |
| 16 | Chapter 8 - Network Security | Network security monitoring and defensive evidence | Packet/log evidence, baseline detection, incident triage, defensive documentation |
| 17 | Drill | Subnetting, routing, and path-selection drill | Chapters 1, 5; WAN/cloud routing; operational validation |
| 18 | Drill | Packet capture and layered troubleshooting drill | Chapters 1, 3, 4, 5, 6; evidence-first troubleshooting |
| 19 | Drill | TCP/UDP socket and service exposure drill | Chapter 6; Beej; Python; firewall checks |
| 20 | Drill | DNS, HTTP, TLS, and application dependency drill | Chapter 7; TLS/PKI; logs; monitoring |
| 21 | Drill | Segmentation, firewall, NAT, and secure access drill | Chapters 4, 5, 8; cybersecurity; cloud/admin controls; Palo Alto/Cisco/Juniper style policy model |
| 22 | Drill | Network automation, inventory, and validation drill | Network Programmability and Automation; Python; YAML/JSON; pre/post checks; source-of-truth thinking |
| 23 | Drill | Incident, runbook, observability, CMDB, and cloud administration drill | Practice of System/Network Administration; Practice of Cloud Administration; tooling landscape assessment; target-state operations |
| 24 | Capstone | Enterprise network operations and tooling strategy capstone | All chapters; cybersecurity; automation; observability; CMDB; cost optimisation; AI-assisted analysis with human validation; target-state tooling strategy |

## Capstone rule

Lab 24 is the final capstone. It should require the learner to combine the whole series into one enterprise-style scenario covering design, troubleshooting, security, automation, observability, CMDB/source-of-truth, cost optimisation, and consulting-quality documentation.

## Reflection rule

The learner solves the lab first. Documentation is handled afterwards from evidence and seven reflection answers.

Ask exactly seven reflection questions for every completed lab.