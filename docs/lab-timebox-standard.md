# Lab Timebox Standard

## Purpose

Every lab in the 24-lab NetworkingLabs curriculum must be designed to fit inside a focused 60-90 minute session.

The maximum expected duration for a normal lab is 1.5 hours.

## Core rule

Each lab should be scoped for:

```text
Minimum target: 60 minutes
Maximum target: 90 minutes
```

A lab should not be generated if the expected work is likely to exceed 90 minutes.

If the story, cumulative repetition, controlled failure/recovery work, official documentation checks, or evidence requirements become too large, reduce the scope of the lab rather than extending the duration.

## Time allocation

A standard lab should aim for this split:

| Section | Target time |
| --- | ---: |
| Story, requirements, references, and planning | 10-15 minutes |
| Part 1 - new chapter or lab-specific content | 20-30 minutes |
| Part 2 - cumulative repetition | 10-20 minutes |
| Controlled fault and recovery | 15-20 minutes |
| Evidence capture and notes | 10-15 minutes |

The exact split may change by lab, but the total should remain within 60-90 minutes.

## Scope control

To keep each lab inside the timebox:

- use one main scenario
- use one primary controlled fault
- limit Part 1 to the most important new concept for that lab
- make Part 2 cumulative but focused
- avoid large multi-service builds unless it is the capstone
- avoid long installation/setup work unless setup is the main point of the lab
- keep documentation evidence concise
- push optional extensions into a separate stretch section

## Stretch work rule

Optional stretch tasks are allowed, but they must be clearly marked as outside the 60-90 minute core lab.

Use this format:

```text
Optional stretch task - not required for lab completion
```

Stretch work must not be needed to complete the lab or answer the reflection questions.

## Capstone exception

Lab 24 is the final SRE-relevant capstone and may be larger than a normal lab if intentionally split into sessions.

If Lab 24 is too large for 90 minutes, it should be broken into clearly labelled sessions, each with its own 60-90 minute timebox.

Example:

```text
Lab 24A - Current-state assessment and incident triage
Lab 24B - Target-state reliability design
Lab 24C - Automation, observability, and final portfolio write-up
```

The capstone remains one lab conceptually, but each working session should still fit within 60-90 minutes.

## Completion standard

A generated lab is not ready unless it includes an estimated duration and the core work is realistically scoped for 60-90 minutes.