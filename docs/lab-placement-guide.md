# Lab Placement Guide

## Purpose

This guide defines where each lab in the 24-lab series should be placed.

Every lab must live in the chapter folder or drill folder that matches its lab number.

## Naming convention

Use lowercase, numbered, hyphenated names.

Example:

```text
01-chapter-01-introduction/lab-01-network-models-and-packet-flow.md
06-chapter-06-transport-layer/lab-12-tcp-udp-socket-service.md
09-drill-labs/lab-24-final-integrated-drill.md
```

## Folder placement

| Folder | Labs | Use for |
| --- | ---: | --- |
| `01-chapter-01-introduction/` | 1-2 | `Computer Networks` Chapter 1: introduction, network uses, network types, protocols, reference models, packet flow, and baseline troubleshooting |
| `02-chapter-02-physical-layer/` | 3-4 | Chapter 2: media, signalling, bandwidth, latency, wireless, access networks, and physical-layer measurement |
| `03-chapter-03-data-link-layer/` | 5-6 | Chapter 3: framing, error control, flow control, ARP/MAC evidence, and link reliability |
| `04-chapter-04-medium-access-control-sublayer/` | 7-8 | Chapter 4: Ethernet, Wi-Fi, switching, bridges, VLANs, shared media, and LAN segmentation |
| `05-chapter-05-network-layer/` | 9-10 | Chapter 5: IP addressing, forwarding, routing, NAT, firewalls, and cloud network design |
| `06-chapter-06-transport-layer/` | 11-12 | Chapter 6: TCP, UDP, ports, sockets, service exposure, connection state, and reliability |
| `07-chapter-07-application-layer/` | 13-14 | Chapter 7: DNS, HTTP, TLS, application dependencies, proxying, APIs, logs, and service health |
| `08-chapter-08-network-security/` | 15-16 | Chapter 8: encryption, TLS/PKI, authentication, access control, monitoring, and defensive evidence |
| `09-drill-labs/` | 17-24 | Integrated practice across all chapters plus Beej, automation, security, cloud/admin practice, AI-assisted analysis, and operations |

## Supporting content placement

Supporting content is integrated inside the 24 labs rather than separated into its own folder.

| Supporting source or topic | How it is used |
| --- | --- |
| `Beej's Guide to Network Programming` | Socket and service labs, especially Labs 11-12 and Drill Lab 19 |
| `Network Programmability and Automation` | Automation, inventory, validation, and repeatable checks, especially Labs 22 and 24 |
| `The Practice of System and Network Administration` | Expected state, change control, evidence, monitoring, runbooks, and operational documentation in every lab |
| `The Practice of Cloud Administration` | Cloud/admin mindset: controlled changes, cost, reliability, access, rollback, monitoring, and ownership in every lab |
| Cybersecurity books and `Bulletproof TLS and PKI` | Security design, TLS/PKI, access control, monitoring, and defensive evidence in Labs 13-16 and Drills 20-21 |
| AI books | AI-assisted troubleshooting, summarisation, hypothesis generation, runbook drafting, and validation in relevant labs and Lab 24 |

## AI rule

AI can be used inside any lab if it supports the objective, but it must be documented and validated.

AI output is not proof. Final evidence must come from commands, logs, packet captures, configuration, tests, diagrams, or source material.

## Future lab upload rule

When a new lab is created, upload it directly to the correct chapter or drill folder using the naming convention above.