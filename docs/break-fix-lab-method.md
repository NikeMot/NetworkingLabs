# Break/Fix Lab Method

## Purpose

Breaking and fixing systems is the core practical method for this lab series.

Every lab should include a controlled failure, a diagnostic process, a fix, verification evidence, and a prevention or production-improvement note.

The goal is to build real troubleshooting judgement rather than only building working examples.

## Safety rule

Break/fix work must only happen inside authorised lab environments owned or controlled by the learner.

Do not break real services, third-party systems, employer systems, public networks, or anything outside the lab scope.

## Required break/fix structure

Each lab should include:

1. Expected healthy state
2. Controlled failure introduced
3. Symptoms observed
4. Initial hypothesis
5. Layer-by-layer diagnostic checks
6. Evidence collected
7. Root cause or likely cause
8. Fix applied
9. Validation that service recovered
10. Prevention, monitoring, alerting, or runbook improvement

## Failure types

Use failures that match the lab topic.

| Area | Example controlled failures |
| --- | --- |
| Physical / access | Wrong interface, disabled adapter, simulated packet loss, poor Wi-Fi/channel design analysis |
| Data link / LAN | Wrong MAC/ARP assumption, VLAN mismatch, bridge/switching path issue, segmentation mistake |
| Network layer | Wrong IP address, subnet mask error, missing route, wrong gateway, broken NAT, asymmetric path |
| Firewall / security | Missing allow rule, wrong source/destination, wrong service object, incorrect rule order, implicit deny |
| Transport | Closed port, service bound to wrong interface, TCP reset/refused connection, UDP listener missing |
| Application | DNS failure, wrong HTTP port, TLS/certificate issue, broken proxy path, unhealthy dependency |
| Observability | Missing check, noisy alert, wrong threshold, incomplete logs, no synthetic test |
| Automation | Bad inventory data, failed validation, unsafe script behaviour, missing rollback condition |
| CMDB/source of truth | Stale inventory, wrong ownership, missing dependency, mismatch between intended and actual state |
| SRE capstone | SLO breach, incident scenario, alert gap, manual toil, rollback decision, cost/reliability trade-off |

## Diagnostic expectation

Troubleshooting should be evidence-led.

The learner should avoid guessing and instead prove or disprove hypotheses using commands, logs, packet evidence, diagrams, configuration, tests, or monitoring output.

## Minimum evidence

Each break/fix section should include:

- the broken state
- the symptom
- at least three diagnostic checks where possible
- the fix
- the recovered state
- what would prevent recurrence

## Production thinking

For every break/fix task, document:

- how this failure could happen in production
- how users would notice it
- what alert or monitoring check should detect it
- what runbook action should exist
- what rollback or safe-change process would reduce risk
- what documentation or CMDB/source-of-truth data should be updated

## SRE alignment

Break/fix work supports SRE skills by training:

- incident triage
- service impact assessment
- dependency mapping
- SLI/SLO thinking
- error budget reasoning
- rollback decisions
- toil reduction
- post-incident improvement
- reliability-focused automation

## Completion standard

A lab is not complete until the learner has broken something safely, fixed it, proved recovery, and recorded how the failure would be detected or prevented in production.