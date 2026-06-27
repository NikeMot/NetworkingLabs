# Controlled Fault and Recovery Lab Standard

## Purpose

Every lab in the 24-lab NetworkingLabs curriculum must include controlled fault and recovery work.

The key practical outcome of the series is that the learner repeatedly creates a safe lab fault, diagnoses the failure, restores service, validates recovery, and documents prevention.

## Core rule

Every lab must include:

```text
1. Build or inspect the expected working state
2. Introduce a controlled lab fault
3. Capture failure evidence
4. Diagnose the fault
5. Restore the working state
6. Validate recovery
7. Document root cause and prevention
```

This applies to all 24 labs, including chapter labs, drill labs, and the SRE capstone.

## Safety and scope

Fault and recovery work must remain controlled, authorised, and lab-contained.

Do not test against systems outside the learner's lab environment.

Do not perform unauthorised testing against third-party networks, services, or applications.

Do not publish secrets, tokens, public IPs, private credentials, or sensitive logs.

## Required sections

Each lab should include:

- expected state
- controlled fault introduced
- failure symptoms
- evidence collected
- hypothesis
- diagnostic steps
- root cause
- recovery action
- recovery validation
- prevention or monitoring recommendation
- production impact if this happened in a real environment

## Fault types by topic

| Area | Example controlled faults |
| --- | --- |
| Network foundations | Missing route, failed reachability check, incorrect layer assumption |
| Physical/access layer | Simulated latency, packet loss, disabled interface, poor signal assumption |
| Data link | ARP confusion, local delivery failure, interface mismatch |
| Switching/VLAN/Wi-Fi | Wrong VLAN, missing trunk, incorrect SSID/security assumption, segmentation failure |
| Network layer | Wrong subnet, missing route, bad gateway, NAT or firewall mismatch |
| Transport layer | Closed port, wrong bind address, TCP/UDP mismatch, blocked service |
| Application layer | DNS failure, HTTP error, TLS/certificate issue, proxy or dependency problem |
| Security | Over-permissive rule, blocked legitimate flow, missing logging, trust-boundary failure |
| Automation | Bad inventory, failed validation, unsafe assumption, drift between desired and actual state |
| Observability | Missing alert, noisy alert, wrong metric, missing log, incomplete dashboard |
| CMDB/source of truth | Missing owner, wrong dependency, stale inventory, incorrect source-of-truth record |
| SRE capstone | Reliability incident, SLO breach, error-budget impact, manual toil, unclear ownership |

## Evidence requirements

The fault and recovery section must include evidence from at least one primary source:

- command output
- packet capture or packet summary
- log excerpt or log summary
- configuration comparison
- validation script output
- monitoring or alerting result
- diagram showing the failure path

AI output does not count as primary evidence.

## Diagnosis standard

Diagnosis should show:

- what was expected
- what was observed
- what layer or dependency was suspected
- what evidence supported or rejected each hypothesis
- why the final root cause was accepted

## Recovery standard

The recovery action should be minimal and explainable.

The learner should record:

- exact change made
- why the change restored service
- how recovery was validated
- whether rollback was possible
- how the issue could be prevented or detected earlier

## Production relevance

Each controlled fault and recovery exercise should include a production note:

- user impact
- business or service impact
- monitoring that should detect it
- alert that should fire
- runbook action
- escalation path
- prevention or automation opportunity

## SRE relevance

For later labs and especially Lab 24, the recovery work should connect to SRE concepts:

- SLI affected
- SLO impact
- error budget impact
- incident severity
- time to detect
- time to mitigate
- time to recover
- toil created
- automation opportunity
- post-incident improvement

## Completion standard

A lab is not complete unless the learner has introduced a controlled fault safely, restored the working state, and provided evidence of both failure and recovery.