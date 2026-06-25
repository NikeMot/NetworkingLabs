# Lab Placement Guide

## Purpose

This guide defines where each networking and cybersecurity lab should be placed.

Every lab must live in the numbered topic folder that matches its main learning objective.

## Naming convention

Use lowercase, numbered, hyphenated names.

Example:

```text
01-network-foundations/lab-01-packet-flow-linux-network-inspection.md
```

## Topic folders

| Folder | Use for |
| --- | --- |
| `01-network-foundations/` | Network models, packet flow, encapsulation, reachability, and baseline troubleshooting |
| `02-linux-network-troubleshooting/` | Linux network commands, local routes, host diagnostics, socket state, and packet inspection |
| `03-tcp-udp-socket-programming/` | TCP and UDP application behaviour, client/server exercises, ports, and message handling |
| `04-ip-addressing-routing/` | Subnetting, gateways, static routes, path selection, and routed topologies |
| `05-switching-vlans-segmentation/` | Switching concepts, VLANs, trunks, segmentation, and inter-VLAN routing |
| `06-firewalls-nat-access-control/` | Filtering, NAT, traffic rules, service exposure, and reachability validation |
| `07-network-services/` | DNS, DHCP/IPAM, NTP, HTTP, reverse proxies, and service dependency labs |
| `08-monitoring-logging-incident-response/` | Monitoring, logs, incident notes, runbooks, recovery notes, and problem management |
| `09-network-programmability-automation/` | Python, structured inventory, APIs, Ansible, validation scripts, and repeatable changes |
| `10-cybersecurity-foundations/` | Core defensive security concepts, risk, least privilege, authentication, encryption, and secure design |
| `11-network-security-monitoring-detection/` | Defensive monitoring, packet evidence, log evidence, baselines, alerts, and incident triage |
| `12-capstone-production-scenarios/` | Integrated scenarios that combine design, troubleshooting, security, automation, documentation, and operations |

## Placement rule

If a lab spans multiple areas, place it in the folder that matches the primary learning objective.

Example: a DNS outage lab with packet capture and incident notes belongs in `07-network-services/` because DNS is the main subject.

Example: a lab about TLS certificates belongs in `10-cybersecurity-foundations/` because the main subject is secure communication.

Example: a lab about reviewing logs and packet evidence belongs in `11-network-security-monitoring-detection/` because the main subject is defensive monitoring.

## Future lab upload rule

When a new lab is created, upload it directly to the correct topic folder using the naming convention above.