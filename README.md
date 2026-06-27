# Networking Labs

## Overview

This repository contains a 24-lab networking, cybersecurity, automation, cloud-operations, and AI-assisted operations curriculum.

The curriculum is based primarily on the eight chapters of `Computer Networks` by Tanenbaum, Feamster, and Wetherall. Each chapter becomes two practical labs, creating 16 chapter labs. After those, there are 8 drill labs designed to reinforce everything learned.

The learner solves the labs. Documentation is produced from the learner's evidence, command output, files created or changed, issues encountered, and answers to seven reflection questions.

## Curriculum structure

| Section | Labs | Basis |
| --- | ---: | --- |
| Chapter labs | 1-16 | Two labs for each of the eight chapters in `Computer Networks` |
| Drill labs | 17-24 | Integrated repetition across networking, security, automation, cloud/admin practice, and AI-assisted operations |

## Repository structure

| Path | Purpose |
| --- | --- |
| `docs/` | Repository-level documentation, standards, lab workflow, and curriculum maps |
| `01-chapter-01-introduction/` | Labs 1-2: network uses, types, protocols, reference models, packet flow, and baseline troubleshooting |
| `02-chapter-02-physical-layer/` | Labs 3-4: media, signals, bandwidth, latency, wireless, access networks, and measurement |
| `03-chapter-03-data-link-layer/` | Labs 5-6: framing, error handling, flow control, ARP/MAC evidence, and link reliability |
| `04-chapter-04-medium-access-control-sublayer/` | Labs 7-8: Ethernet, Wi-Fi, switching, VLANs, bridging, segmentation, and LAN security |
| `05-chapter-05-network-layer/` | Labs 9-10: IP addressing, routing, forwarding, NAT, cloud routing, and network-layer troubleshooting |
| `06-chapter-06-transport-layer/` | Labs 11-12: TCP, UDP, ports, sockets, connection state, congestion, and service exposure |
| `07-chapter-07-application-layer/` | Labs 13-14: DNS, HTTP, TLS, application dependencies, service health, logs, and proxies |
| `08-chapter-08-network-security/` | Labs 15-16: encryption, TLS/PKI, authentication, access control, monitoring, and defensive evidence |
| `09-drill-labs/` | Labs 17-24: repeated challenge labs across the whole curriculum |
| `scripts/` | Reusable helper scripts for validation, health checks, parsing, reporting, and AI-assisted tooling |

## Main references

Primary base:

- `Computer Networks`, Sixth Edition, Global Edition — Tanenbaum, Feamster, and Wetherall

Supporting sources integrated across the 24 labs:

- `Beej's Guide to Network Programming`
- `Network Programmability and Automation`
- `The Practice of System and Network Administration`
- `The Practice of Cloud Administration`
- `Computer Networking: A Top-Down Approach`
- `Bulletproof TLS and PKI`
- security and cybersecurity books from the Drive security folders
- `AI Engineering`
- `AI Systems Performance Engineering`
- `Hands-On Large Language Models`
- `Prompt Engineering for LLMs`

## Operating method

Every lab should be performed like operational engineering work:

- define the expected state
- make a controlled change
- collect evidence
- validate the result
- document issues and fixes
- consider security, reliability, monitoring, rollback, and cloud/admin implications
- use AI only as an assistant and validate its output with primary evidence

## Lab naming convention

Use lowercase, numbered, hyphenated names.

Examples:

```text
01-chapter-01-introduction/lab-01-network-models-and-packet-flow.md
06-chapter-06-transport-layer/lab-12-tcp-udp-socket-service.md
09-drill-labs/lab-24-final-integrated-drill.md
```
