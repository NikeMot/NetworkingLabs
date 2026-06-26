# Networking Labs

## Overview

This repository contains hands-on networking, cybersecurity, and AI-assisted operations labs for developing junior network engineering, systems administration, SRE, network automation, defensive security, and practical AI skills.

The lab series moves from packet-level fundamentals to production-style troubleshooting, automation, secure design, defensive monitoring, and AI-assisted operational analysis. Each lab should produce evidence: commands, diagrams, packet analysis, configuration, troubleshooting notes, operational decisions, security decisions, AI-assisted analysis where relevant, and reflection.

## Skills covered

| Area | Status | Topics |
| --- | --- | --- |
| Network foundations | Not started | OSI/TCP-IP models, packet flow, encapsulation, reachability |
| Linux network troubleshooting | Not started | Linux network commands, packet capture, routes, sockets |
| TCP/UDP socket programming | Not started | clients, servers, ports, binding, connection state, message framing |
| IP addressing and routing | Not started | subnetting, static routes, gateways, path selection |
| Switching, VLANs, and segmentation | Not started | VLANs, trunks, inter-VLAN routing, segmentation |
| Firewalls, NAT, and access control | Not started | filtering, NAT/PAT, service exposure, policy validation |
| Network services | Not started | DNS, DHCP/IPAM, NTP, HTTP, reverse proxies |
| Monitoring, logging, and incident response | Not started | health checks, logs, packet evidence, incidents, runbooks |
| Network programmability and automation | Not started | Python, YAML/JSON inventory, APIs, Ansible, automation, validation |
| Cybersecurity foundations | Not started | CIA triad, threat modelling, authentication, encryption, least privilege, risk |
| Network security monitoring and detection | Not started | defensive packet analysis, log review, secure baselines, alerting, evidence handling |
| AI-assisted networking and security operations | Not started | prompt engineering, AI-assisted troubleshooting, log summarisation, runbook generation, validation |
| Capstone production scenarios | Not started | design, build, break, troubleshoot, secure, automate, analyse, document, improve |

## Repository structure

| Path | Purpose |
| --- | --- |
| `docs/` | General documentation, decisions, standards, templates, and lab placement rules |
| `01-network-foundations/` | Network models, packet flow, encapsulation, and baseline troubleshooting |
| `02-linux-network-troubleshooting/` | Linux network inspection, diagnostic commands, packet capture, and evidence gathering |
| `03-tcp-udp-socket-programming/` | TCP/UDP behaviour, sockets, ports, binding, listening, and client/server tools |
| `04-ip-addressing-routing/` | Subnetting, routes, gateways, path selection, and routed lab topologies |
| `05-switching-vlans-segmentation/` | Switching concepts, VLANs, trunks, segmentation, and inter-VLAN routing |
| `06-firewalls-nat-access-control/` | Firewalls, ACLs, NAT, PAT, least-privilege access, and policy validation |
| `07-network-services/` | DNS, DHCP/IPAM, NTP, HTTP, reverse proxies, and production service dependencies |
| `08-monitoring-logging-incident-response/` | Observability, logging, alerting, incidents, problem management, and runbooks |
| `09-network-programmability-automation/` | Python automation, YAML/JSON inventory, APIs, Ansible, and validation |
| `10-cybersecurity-foundations/` | Core defensive security concepts that support networking and system administration |
| `11-network-security-monitoring-detection/` | Defensive monitoring, detection, packet evidence, log evidence, and secure baselines |
| `12-ai-assisted-networking-security-operations/` | Practical AI use for troubleshooting, analysis, documentation, and validation in network/security operations |
| `13-capstone-production-scenarios/` | Integrated scenarios combining design, troubleshooting, security, AI-assisted analysis, automation, and operations |
| `scripts/` | Reusable helper scripts for validation, health checks, parsing, and reporting |

## Lab naming convention

Use lowercase, numbered, hyphenated names.

```text
01-network-foundations/lab-01-packet-flow-linux-network-inspection.md
10-cybersecurity-foundations/lab-49-security-principles-for-network-engineers.md
12-ai-assisted-networking-security-operations/lab-57-ai-assisted-log-analysis-and-validation.md
13-capstone-production-scenarios/lab-65-final-secure-network-operations-capstone.md
```

## Main references

- Computer Networks
- Computer Networking: A Top-Down Approach
- Beej's Guide to Network Programming
- Network Programmability and Automation
- The Practice of System and Network Administration
- Bulletproof TLS and PKI
- AI Engineering
- AI Systems Performance Engineering
- Hands-On Large Language Models
- Prompt Engineering for LLMs
- Security and cybersecurity books from the Drive security folders
