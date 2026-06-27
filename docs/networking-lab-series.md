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

## Two-part lab rule

Every lab must have two parts:

```text
Part 1 - New chapter or lab-specific content
Part 2 - Cumulative repetition of all topics learned so far
```

For Labs 1-16, Part 1 is based on the assigned full `Computer Networks` chapter.

For Labs 17-23, Part 1 is based on the drill theme.

For Lab 24, Part 1 is the SRE-relevant enterprise capstone scenario.

Part 2 must repeat and apply all topics learned so far, including the current lab. It should produce practical evidence, not just written recall.

## Target job alignment

The curriculum is designed to build portfolio evidence for:

- advanced network troubleshooting and diagnostics
- enterprise LAN, WAN, and Wi-Fi architecture
- network performance and availability management
- network security and firewall policy reasoning, including Cisco, Juniper, and Palo Alto style concepts
- network automation, validation, and source-of-truth thinking
- observability tooling, management tooling, and CMDB strategy
- SRE-relevant reliability engineering, SLI/SLO thinking, incident response, and toil reduction
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

| Lab | Base chapter / type | Part 1 new content | Part 2 cumulative repetition |
| ---: | --- | --- | --- |
| 1 | Chapter 1 - Introduction | Network models and packet flow baseline | Repeat Lab 1 fundamentals: layers, packet flow, expected state, evidence |
| 2 | Chapter 1 - Introduction | Protocol layering, services, tooling landscape, and troubleshooting method | Repeat Labs 1-2: layering, packet flow, service dependencies, evidence capture |
| 3 | Chapter 2 - Physical Layer | Media, bandwidth, latency, WAN access, and measurement | Repeat Labs 1-3: layers, service mapping, physical/access network measurement |
| 4 | Chapter 2 - Physical Layer | Loss, throughput, availability, and physical-layer fault isolation | Repeat Labs 1-4: expected state, latency/loss, availability, troubleshooting notes |
| 5 | Chapter 3 - Data Link Layer | Frames, MAC addresses, ARP, and local delivery | Repeat Labs 1-5: packet flow, physical path, ARP/MAC evidence, local delivery |
| 6 | Chapter 3 - Data Link Layer | Error handling, flow control, and link reliability | Repeat Labs 1-6: link reliability, packet evidence, availability checks, documentation |
| 7 | Chapter 4 - MAC Sublayer | Ethernet switching, bridges, and VLAN segmentation | Repeat Labs 1-7: packet flow, ARP, switching, VLAN segmentation, evidence |
| 8 | Chapter 4 - MAC Sublayer | Wireless LANs, shared media, and secure LAN design | Repeat Labs 1-8: Wi-Fi, LAN segmentation, trust boundaries, monitoring notes |
| 9 | Chapter 5 - Network Layer | IP addressing, subnetting, forwarding, and routing | Repeat Labs 1-9: subnetting, routes, switching, physical evidence, packet flow |
| 10 | Chapter 5 - Network Layer | NAT, firewalls, path troubleshooting, and cloud network design | Repeat Labs 1-10: routing, NAT, firewall rules, segmentation, rollback evidence |
| 11 | Chapter 6 - Transport Layer | TCP handshake, connection state, reliability, and congestion | Repeat Labs 1-11: path, routing, firewall, TCP state, service health evidence |
| 12 | Chapter 6 - Transport Layer | UDP, TCP sockets, ports, and service exposure | Repeat Labs 1-12: socket exposure, port checks, firewall validation, packet capture |
| 13 | Chapter 7 - Application Layer | DNS, HTTP, TLS, and application dependency mapping | Repeat Labs 1-13: DNS, routes, TCP, firewall, TLS, service dependency evidence |
| 14 | Chapter 7 - Application Layer | Application troubleshooting with logs, proxies, APIs, and observability | Repeat Labs 1-14: logs, DNS, HTTP, TLS, proxy path, monitoring gaps |
| 15 | Chapter 8 - Network Security | Security principles, TLS/PKI, identity, least privilege, and firewall policy | Repeat Labs 1-15: security decisions across LAN, WAN, routing, transport, app layers |
| 16 | Chapter 8 - Network Security | Network security monitoring and defensive evidence | Repeat Labs 1-16: defensive monitoring, packet/log evidence, incident triage |
| 17 | Drill | Subnetting, routing, and path-selection drill | Repeat Labs 1-17 with emphasis on route design, path validation, and availability |
| 18 | Drill | Packet capture and layered troubleshooting drill | Repeat Labs 1-18 with emphasis on layered diagnostics and packet evidence |
| 19 | Drill | TCP/UDP socket and service exposure drill | Repeat Labs 1-19 with emphasis on service exposure, firewall checks, and sockets |
| 20 | Drill | DNS, HTTP, TLS, and application dependency drill | Repeat Labs 1-20 with emphasis on application dependencies and TLS trust |
| 21 | Drill | Segmentation, firewall, NAT, and secure access drill | Repeat Labs 1-21 with emphasis on secure access, firewall policy, and trust boundaries |
| 22 | Drill | Network automation, inventory, and validation drill | Repeat Labs 1-22 with emphasis on automation, source of truth, and validation |
| 23 | Drill | Incident, runbook, observability, CMDB, and cloud administration drill | Repeat Labs 1-23 with emphasis on incident handling, observability, CMDB, and cloud operations |
| 24 | SRE Capstone | Enterprise network reliability, operations, and tooling strategy capstone | Repeat Labs 1-24 through full SRE-relevant capstone integration across design, troubleshooting, security, automation, observability, CMDB, cost, SLOs, incident response, toil reduction, and AI validation |

## Capstone rule

Lab 24 is the final SRE-relevant capstone. It should require the learner to combine the whole series into one enterprise-style reliability scenario covering service ownership, user impact, design, troubleshooting, security, automation, observability, CMDB/source-of-truth, SLI/SLO thinking, error budget reasoning, incident response, toil reduction, cost optimisation, and consulting-quality documentation.

## Reflection rule

The learner solves both parts of the lab first. Documentation is handled afterwards from evidence and seven reflection answers.

Ask exactly seven reflection questions for every completed lab.