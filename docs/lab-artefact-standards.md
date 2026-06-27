# Lab Artefact Standards

## Purpose

This document defines the artefacts that should be produced across the 24-lab NetworkingLabs curriculum.

The learner solves the practical lab. Documentation is then created from the learner's evidence and seven reflection answers.

## Two-part artefact rule

Every lab must produce artefacts for two parts:

```text
Part 1 - New chapter or lab-specific content
Part 2 - Cumulative repetition of all topics learned so far
```

Part 1 proves the learner understood and applied the new material.

Part 2 proves the learner can retrieve, combine, and apply earlier material without treating previous labs as finished and forgotten.

## Minimum artefacts for every lab

Every completed lab should include:

- lab summary
- scenario
- full chapter or full reference reading used
- requirements for Part 1 and Part 2
- constraints
- assumptions
- Part 1 implementation summary
- Part 2 cumulative repetition summary
- key commands or tools used
- files created or changed
- verification evidence for both parts
- cumulative repetition coverage
- diagram where useful
- issues encountered
- decisions made
- security and production considerations
- tooling, observability, and source-of-truth notes where relevant
- AI usage and validation if AI was used
- final outcome
- what was learned
- what would be improved in production
- references used
- seven reflection answers

## Evidence standards

Evidence should be specific enough that another engineer can understand what happened.

Good evidence includes:

- command and output summaries
- packet capture summaries
- screenshots described in text
- configuration snippets that are safe to publish
- log excerpts that are safe to publish
- diagrams
- tables
- test results
- monitoring checks
- validation reports
- before/after comparisons
- cumulative repetition evidence

Do not include sensitive material in public documentation.

## Part 1 evidence standards

Part 1 evidence should prove the new lab content was completed.

Examples:

- command-output summary for the new task
- packet evidence for the new protocol or layer
- new diagram or design decision
- new configuration or script result
- new troubleshooting finding
- new monitoring or security recommendation

## Part 2 evidence standards

Part 2 evidence should prove earlier topics were repeated and applied.

Examples:

- short layered troubleshooting check
- previous command repeated in a new context
- previous packet-analysis method reused
- previous subnetting/routing decision reused
- previous firewall or segmentation model reused
- previous DNS/HTTP/TLS validation reused
- previous automation or source-of-truth idea reused
- previous observability or alerting idea reused

## Diagram standards

Use diagrams for:

- topology
- packet flow
- traffic flow
- failure path
- service dependency
- firewall zone model
- observability data flow
- CMDB/source-of-truth model
- automation workflow
- capstone architecture

Mermaid diagrams are acceptable for Markdown-first documentation.

## Troubleshooting standards

Troubleshooting labs should include:

- symptom
- expected state
- observed state
- layer-by-layer checks
- evidence collected
- likely cause
- fix or workaround
- validation
- prevention or monitoring recommendation

## Security standards

Security-related labs should include:

- asset or service being protected
- trust boundary
- threat or risk
- control used
- validation evidence
- logging or monitoring implication
- production improvement

## Network design standards

Design-related labs should include:

- requirements
- assumptions
- constraints
- topology
- addressing or segmentation plan
- routing or policy design
- resilience and availability considerations
- cost trade-offs
- security trade-offs
- monitoring approach
- operational ownership

## Automation standards

Automation-related labs should include:

- input source
- expected state
- script or tool used
- pre-checks
- action or analysis performed
- post-checks
- output report
- error handling
- rollback or safe exit consideration

## Observability standards

Observability-related labs should include:

- metrics
- logs
- events
- packet evidence where relevant
- health checks
- alert candidates
- dashboard candidates
- runbook action
- escalation criteria

## CMDB/source-of-truth standards

CMDB or source-of-truth work should include:

- inventory entities
- relationship model
- ownership fields
- service dependency fields
- source-of-truth format
- how the data is validated
- how the data would support automation or troubleshooting

## Cost optimisation standards

Cost or solution design work should include:

- options compared
- cost drivers
- performance trade-offs
- resilience trade-offs
- operational trade-offs
- recommended option
- reason for recommendation

## AI standards

When AI is used, record:

- prompt or prompt summary
- AI output summary
- how the output was checked
- what was useful
- what was wrong or incomplete
- whether it changed the final decision

AI output is not evidence by itself.

## SRE capstone standards

Lab 24 should be SRE-relevant and include all major artefact types:

- enterprise reliability scenario
- user-facing impact statement
- service ownership model
- current-state assessment
- target-state design
- topology diagram
- traffic-flow diagram
- service dependency map
- failure-mode analysis
- SLI/SLO table
- error budget notes
- incident timeline
- troubleshooting evidence
- packet, log, and metric evidence summary
- security model
- firewall policy model
- monitoring and observability strategy
- CMDB/source-of-truth model
- automation and validation plan
- toil reduction plan
- rollback or safe-change plan
- cost and reliability trade-off notes
- implementation roadmap
- risks and assumptions
- executive summary
- technical appendix
- Part 1 capstone implementation evidence
- Part 2 full-curriculum repetition evidence
- seven reflection answers

Lab 24 should demonstrate both network engineering competence and SRE judgement.