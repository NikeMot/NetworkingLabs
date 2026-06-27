# SRE Capstone Requirements

## Purpose

Lab 24 is the final capstone for the 24-lab NetworkingLabs curriculum.

The capstone must be SRE-relevant. It should prove the learner can reason about reliability, incidents, observability, automation, service ownership, risk, cost, and operational improvement in an enterprise network environment.

## Capstone theme

Lab 24 should simulate an enterprise service reliability scenario where network behaviour affects service availability, performance, security, and operational efficiency.

The learner should act as an SRE-minded infrastructure/network engineer who must assess current state, troubleshoot problems, design target state, and define operational improvements.

## Required SRE concepts

Lab 24 must include:

- service ownership
- user-facing impact
- service dependency mapping
- SLI definition
- SLO target
- error budget reasoning
- availability and latency analysis
- incident response
- escalation criteria
- runbook actions
- post-incident improvement
- monitoring and alerting strategy
- logs, metrics, and packet evidence
- automation and validation
- toil identification and reduction
- rollback or safe-change plan
- capacity and performance considerations
- cost and reliability trade-offs
- security and access-control implications
- target-state tooling strategy

## Suggested SRE scenario

A realistic capstone scenario should include:

- an enterprise application with users in multiple locations
- LAN, WAN, Wi-Fi, firewall, DNS, TLS, and application dependencies
- intermittent performance or availability symptoms
- unclear ownership between network, cloud, security, and application teams
- incomplete monitoring and CMDB/source-of-truth data
- manual troubleshooting steps that create toil
- a need to define a target-state tooling and reliability strategy

## Required artefacts

The Lab 24 write-up should include:

- executive summary
- current-state architecture
- target-state architecture
- service dependency map
- topology diagram
- traffic-flow diagram
- failure-mode analysis
- SLI/SLO table
- error budget notes
- incident timeline
- troubleshooting evidence
- packet/log/metric evidence summary
- monitoring and alerting proposal
- runbook actions
- automation and validation plan
- CMDB/source-of-truth model
- firewall and security policy model
- cost and reliability trade-off table
- toil reduction plan
- implementation roadmap
- risks and assumptions
- post-incident learning summary
- seven reflection answers

## SLI/SLO examples

Potential SLIs:

- availability of the user-facing service
- DNS success rate
- TCP connection success rate
- HTTP success rate
- request latency
- packet loss across WAN path
- TLS certificate validity
- firewall policy hit or deny rate
- synthetic check success rate

Potential SLOs:

- 99.9% monthly availability for the user-facing service
- 95% of successful HTTP requests below an agreed latency threshold
- DNS resolution success above an agreed threshold
- critical synthetic checks passing from required locations
- no expired production TLS certificates

The exact SLOs should be chosen based on the lab scenario and justified in the write-up.

## Error budget rule

The capstone should explain how much unreliability is acceptable before engineering work must prioritise reliability over feature or change velocity.

The learner should document:

- the chosen SLO
- what counts as bad events
- how the error budget is consumed
- what operational decisions follow when the budget is healthy, low, or exhausted

## Incident response requirement

The capstone should include an incident-style workflow:

- detect
- triage
- scope impact
- identify likely layer or dependency
- collect evidence
- mitigate
- validate recovery
- communicate status
- document follow-up work
- prevent recurrence

## Toil reduction requirement

The capstone should identify manual, repetitive, automatable work.

For each toil item, document:

- manual task
- why it is toil
- proposed automation or process improvement
- validation method
- risk of automation
- expected benefit

## Target-state tooling requirement

The capstone should define how tools should work together.

At minimum, include:

- source of truth / CMDB
- monitoring
- logging
- packet analysis
- automation and validation
- incident management
- documentation and runbooks
- security/firewall visibility
- AI-assisted analysis with human validation

## Completion standard

Lab 24 is complete only when it demonstrates both network engineering competence and SRE judgement.

The final output should be suitable as a portfolio artefact for SRE, infrastructure engineering, network automation, observability, or network consulting roles.