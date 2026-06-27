# Repository Design Decision

## Context

This repository contains a 24-lab networking curriculum based on the eight main chapters of `Computer Networks`, Sixth Edition, Global Edition by Tanenbaum, Feamster, and Wetherall.

The user wants a smaller, focused lab series rather than a broad 72-lab roadmap.

The curriculum must still cover the earlier supporting material: Beej's socket programming, Network Programmability and Automation, cybersecurity, AI-assisted operations, system/network administration practice, and cloud administration practice.

## Decision

Use one repository divided into chapter-based folders.

Each of the eight `Computer Networks` chapters gets one folder and two labs. A final drill folder contains eight integrated practice labs.

```text
8 chapters x 2 labs = 16 chapter labs
8 drill labs = 24 labs total
```

## Rationale

Using `Computer Networks` as the spine keeps the curriculum coherent and theory-led. Two labs per chapter gives enough repetition to turn each chapter into practical skill without making the series too large.

The drill labs ensure the learner practises the material repeatedly rather than only completing one-off chapter exercises.

The system/network administration and cloud administration books are used as the method for performing tasks: expected state, change control, validation, monitoring, rollback, ownership, cost awareness, reliability, and documentation.

## Folder naming convention

Use lowercase, numbered, hyphenated folder names.

Examples:

```text
01-chapter-01-introduction
06-chapter-06-transport-layer
09-drill-labs
```

## Alternatives considered

| Alternative | Reason it was not chosen |
| --- | --- |
| 72-lab roadmap | Too large for the current goal and less tightly mapped to the main book |
| One repository per lab | Too many repositories and harder to review as one learning path |
| One flat folder | Difficult to navigate once the lab count grows |
| Separate cybersecurity or AI tracks | Security and AI are better integrated into the networking labs and drills |
| Notes-only repository | Does not prove practical implementation, troubleshooting, or operational judgement |

## Consequences

This structure is smaller and more focused, but each lab must be richer.

Each lab should combine theory, implementation, evidence collection, troubleshooting, operations, security, automation, cloud/admin thinking, and AI validation where relevant.

## Future changes

The 24-lab structure should remain the default unless the user explicitly asks to expand it. Future additions should normally be added as optional extension labs rather than changing the core curriculum size.