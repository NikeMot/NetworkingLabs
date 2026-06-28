# Story-Driven Lab Standard

## Purpose

Every lab in this repository must be story-driven and requirements-led.

The learner should never feel that they are typing commands for no reason. Each command, configuration change, check, diagram, and decision must connect to a realistic engineering situation.

## Core rule

Every generated lab must answer these questions before any task list appears:

1. Who am I in this scenario?
2. What team or organisation am I working for?
3. What service, system, user group, or business process is affected?
4. What request, incident, risk, or improvement triggered the work?
5. Why does this work matter operationally?
6. What outcome would a manager, senior engineer, customer, or user expect?
7. What evidence proves the work was done correctly?

## Required story sections

Every lab must include the following sections.

### 1. Role and context

Define the learner's role.

Examples:

- junior platform engineer joining an SRE team
- network engineer supporting a branch-office outage
- infrastructure engineer preparing a production change
- SRE investigating service latency
- consultant assessing a client's tooling and observability gaps

### 2. Service or system context

Explain the system being worked on.

This may include:

- application or service name
- user group affected
- network path
- dependency chain
- cloud or on-premises environment
- security boundary
- operational owner
- monitoring or documentation gap

### 3. Trigger

Explain why the work is happening now.

The trigger can be:

- incident
- change request
- audit finding
- reliability risk
- onboarding task
- migration requirement
- performance complaint
- security concern
- documentation gap
- automation opportunity
- capstone consulting engagement

### 4. Manager or stakeholder request

Every lab should include a short quoted request from a manager, senior engineer, customer, security reviewer, or incident commander.

Example:

> Do not just make it work. Prove what changed, explain why it matters, and show how we would detect this failure in production.

### 5. Why this matters

Explain the operational reason for the lab.

This section should connect the task to:

- reliability
- security
- availability
- performance
- cost
- auditability
- change control
- incident response
- observability
- SRE practice
- production readiness
- professional documentation

### 6. Requirements-led work

The lab should provide requirements and outcomes, not a copy-paste command script.

Commands may be suggested, but the learner must understand why they are being used and what evidence they produce.

### 7. Evidence-led completion

The lab is complete only when the learner can show:

- what they intended to do
- what they changed or tested
- what broke or failed
- how they diagnosed it
- how they restored or validated the expected state
- what evidence supports the result
- what would matter in production

## Command rule

No command should appear without a purpose.

When commands are suggested, the lab should explain:

- what the command proves
- what output the learner should inspect
- how the output affects the next decision
- what a suspicious or failed output might mean

## Break/fix story rule

Controlled failure work must also have a story.

Do not say only:

```text
Break DNS and fix it.
```

Instead say why the failure matters:

```text
Users in one branch office report that the application is down, but the service itself appears healthy. You suspect DNS, routing, or firewall policy. Create a safe lab version of this failure, gather evidence, identify the fault, restore service, and document how production monitoring should detect it earlier.
```

## Two-part lab story rule

Part 1 and Part 2 must both have context.

Part 1 should explain why the new concept is needed.

Part 2 should explain why cumulative repetition matters for this scenario.

Example:

```text
Part 1 introduces DNS and HTTP because the incident appears application-facing.
Part 2 repeats routing, TCP, firewall, and packet-capture checks because application symptoms often originate in lower layers.
```

## Documentation style

Write labs as operational briefs, not tutorials.

A lab should feel like:

- a ticket
- an incident brief
- a change request
- a consulting engagement
- a reliability investigation
- an audit or security finding
- a production-readiness task

It should not feel like:

- a random command list
- a worksheet with no context
- a copy-paste walkthrough
- an exam cram note

## Completion standard

A lab is not ready to be generated unless it contains a clear story, role, trigger, reason, requirements, evidence expectations, production relevance, and controlled fault/recovery scenario.