# Tooling and Observability Strategy

## Purpose

This document defines the tooling and observability expectations for the 24-lab NetworkingLabs curriculum.

The goal is to build evidence for enterprise network operations, network automation, observability capability design, CMDB/source-of-truth thinking, and target-state tooling strategy.

## Tooling principles

Every lab should consider:

- what tools are available now
- what evidence each tool can produce
- what gaps remain
- what the target-state toolchain should include
- how the tool supports troubleshooting, availability, security, automation, or reporting
- how tool output should be validated

## Baseline diagnostic tools

| Tool type | Examples | Used for |
| --- | --- | --- |
| Interface and route inspection | `ip`, `ipconfig`, `route`, `netstat`, `ss` | Local state, routes, sockets, listening services |
| Reachability testing | `ping`, `traceroute`, `tracert`, `mtr`, `Test-NetConnection` | Path checks, latency, packet loss, port reachability |
| DNS tools | `dig`, `nslookup`, `Resolve-DnsName` | Name resolution, resolver behaviour, DNS failure isolation |
| HTTP/API tools | `curl`, browser dev tools, Postman-style checks | Application reachability, headers, status codes, TLS inspection |
| Packet tools | Wireshark, `tcpdump`, `tshark` | Packet evidence, protocol behaviour, troubleshooting proof |
| TLS tools | `openssl`, browser certificate view, TLS scanners in safe lab context | Certificate chain, TLS version, cipher, expiry, trust validation |

## Observability model

Each relevant lab should identify:

- metrics
- logs
- events
- traces or request flow where applicable
- synthetic checks
- packet evidence
- dashboards
- alerts
- escalation criteria
- runbook actions

## Network performance and availability

Performance and availability labs should capture:

- latency
- packet loss
- jitter where relevant
- throughput where safely measurable
- DNS response behaviour
- TCP connection behaviour
- HTTP response status and timing
- service health
- interface state
- route/path changes

## CMDB and source-of-truth model

Labs involving design, automation, tooling, or capstone work should define a lightweight source-of-truth model.

Minimum useful entities:

- sites
- devices
- interfaces
- VLANs
- subnets
- IP addresses
- routes
- firewall zones
- firewall rules
- services
- owners
- dependencies
- monitoring checks
- runbooks

Acceptable lab formats:

- YAML inventory
- JSON inventory
- CSV inventory
- Markdown CMDB table
- NetBox-style model design

## Automation and validation model

Automation labs should include:

- input data
- expected state
- script or tool action
- pre-checks
- change or analysis step
- post-checks
- failure handling
- rollback or safe exit
- evidence output

Useful outputs include:

- validation report
- failed checks list
- generated diagram data
- generated inventory summary
- route or service comparison
- monitoring target list

## Target-state tooling strategy

Labs 22-24 should produce target-state tooling artefacts.

A target-state tooling strategy should include:

- current tooling landscape
- gaps and pain points
- required capabilities
- proposed tooling categories
- source-of-truth approach
- monitoring and observability approach
- automation approach
- security and access model
- data flow between tools
- ownership model
- implementation phases
- risks and assumptions

## Suggested target-state categories

| Category | Purpose |
| --- | --- |
| Source of truth / CMDB | Inventory, relationships, ownership, intended state |
| Monitoring | Metrics, health checks, availability, performance |
| Logging | Searchable operational and security events |
| Packet analysis | Deep protocol evidence and escalation support |
| Automation | Repeatable changes, validation, reporting, drift detection |
| Documentation | Runbooks, diagrams, decisions, service maps |
| Incident management | Triage records, status, escalation, problem follow-up |
| Security tooling | Firewall policy visibility, access review, threat monitoring |
| AI-assisted analysis | Summaries, hypotheses, documentation drafts, validation support |

## AI use in observability

AI can support observability work by:

- summarising logs
- clustering symptoms
- drafting incident summaries
- generating hypotheses
- comparing current state with expected state
- drafting runbooks
- explaining packet traces
- identifying missing evidence

AI must not be treated as evidence by itself. Its output must be checked against commands, logs, packets, configuration, tests, or documentation.

## Completion standard

A lab that claims observability, tooling, or automation competence should include:

- current-state evidence
- target-state recommendation
- at least one metric, log, packet, configuration, or script output
- an operational decision
- a monitoring or alerting recommendation
- a documentation or runbook improvement
