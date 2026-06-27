# Cybersecurity Track

## Purpose

This document defines the integrated cybersecurity track for the 24-lab NetworkingLabs curriculum.

Cybersecurity is not a separate side path. It is embedded into the networking, cloud administration, automation, observability, and capstone work.

## Scope

The track is defensive and enterprise-focused.

It covers:

- security principles and the CIA triad
- risk, impact, and business context
- threat modelling and trust boundaries
- segmentation and least privilege
- secure LAN, WAN, Wi-Fi, and cloud network design
- NAT, firewall rules, and traffic policy reasoning
- Cisco, Juniper, and Palo Alto style firewall concepts
- TLS, certificates, and PKI
- authentication and authorisation concepts
- secure configuration and controlled change
- packet and log evidence
- network security monitoring
- incident triage and defensive documentation
- secure automation and validation
- AI-assisted analysis with human verification

## Lab coverage

| Lab | Security focus |
| ---: | --- |
| 1 | Security as part of network purpose, policy, privacy, and reliability |
| 2 | Service ownership, dependency mapping, change records, and source-of-truth thinking |
| 3 | Physical media, access network risk, and availability impact |
| 4 | Loss, degradation, availability, and performance-impact evidence |
| 5 | Local delivery evidence, ARP/MAC assumptions, and packet visibility |
| 6 | Link reliability, error handling, and operational validation |
| 7 | VLANs, segmentation, switching boundaries, and production design |
| 8 | Wi-Fi security, guest segmentation, shared media risk, and trust boundaries |
| 9 | IP addressing, subnet design, route scope, and cloud routing control |
| 10 | NAT, firewall policy, security rules, path validation, and rollback |
| 11 | TCP state, exposed services, listening ports, and service health |
| 12 | Socket exposure, port validation, firewall testing, and safe lab-only service exposure |
| 13 | DNS, HTTP, TLS, certificates, service dependency, and application trust |
| 14 | Logs, proxies, APIs, application troubleshooting, and observability gaps |
| 15 | Security principles, TLS/PKI, identity, least privilege, and firewall policy |
| 16 | Network security monitoring, defensive evidence, baseline detection, and triage |
| 17 | Routing and subnetting mistakes as security and availability risks |
| 18 | Packet capture as troubleshooting and defensive evidence |
| 19 | Service exposure and transport-layer access validation |
| 20 | DNS, HTTP, TLS, and dependency failure as security and reliability risks |
| 21 | Segmentation, firewall, NAT, secure access, and vendor-style policy models |
| 22 | Secure automation, validation checks, inventory quality, and source-of-truth integrity |
| 23 | Incident, runbook, observability, CMDB, and cloud administration controls |
| 24 | Capstone: enterprise security design, monitoring, automation, tooling, and evidence |

## Firewall policy model

Firewall-related labs should use a vendor-neutral policy model that maps well to Palo Alto, Cisco, and Juniper environments.

Each firewall task should consider:

- zones or security domains
- interfaces and subinterfaces
- source and destination networks
- source and destination objects
- application or service objects
- NAT policy
- security policy
- rule order
- implicit deny behaviour
- logging and evidence
- rollback plan
- change record

## Wi-Fi security model

Wi-Fi-related labs should cover:

- SSID purpose
- guest versus corporate network separation
- WPA2/WPA3 concepts
- 2.4 GHz, 5 GHz, and 6 GHz design trade-offs
- channel overlap and interference
- roaming concepts
- signal quality and availability impact
- wireless troubleshooting evidence

## Defensive monitoring model

Monitoring labs should define:

- expected traffic
- unexpected traffic
- allowed services
- denied traffic
- noisy signals
- alert thresholds
- logs required for triage
- packet evidence required for escalation
- incident notes
- follow-up prevention work

## Completion standard

A lab has not demonstrated cybersecurity competence until it includes:

- a security decision
- evidence that supports the decision
- a risk or trade-off
- a production consideration
- a monitoring or logging implication
- a clear statement of what would be improved in a real environment
