# Repository Design Decision

## Context

This repository will contain a sequence of networking, cybersecurity, and AI-assisted operations labs covering packet-level fundamentals, Linux troubleshooting, socket programming, routed networks, switching, network services, monitoring, incident response, network automation, secure design, defensive security operations, and practical AI support for technical analysis.

The repository needs to stay understandable as the number of labs grows.

## Decision

Use one repository divided into numbered topic folders. Each folder represents a major networking, defensive security, or AI-assisted operations skill area. Individual labs live inside the relevant topic folder.

## Rationale

A single repository presents the labs as one connected learning path. Numbered folders make the learning order obvious. Topic-based folders make it easier to place future labs correctly.

Cybersecurity is included because networking and security are closely linked in real infrastructure work. Network engineers need to understand segmentation, filtering, encryption, identity, logging, monitoring, and defensive evidence handling.

AI is included because modern infrastructure teams increasingly use AI tools to assist with troubleshooting, documentation, summarisation, runbook drafting, and analysis. AI should support engineering judgement, not replace it.

## Folder naming convention

Use lowercase, numbered, hyphenated folder names.

Examples:

```text
01-network-foundations
10-cybersecurity-foundations
12-ai-assisted-networking-security-operations
13-capstone-production-scenarios
```

## Alternatives considered

| Alternative | Reason it was not chosen |
| --- | --- |
| One repository per lab | Too many repositories and harder to review as a learning path |
| One flat folder | Difficult to navigate once the lab count grows |
| Notes only in the README | The README would become too long |
| Random topic folders | Harder to see progression and maintain consistent placement |
| Separate cybersecurity repository | Security is part of networking and system administration, so separating it would weaken the integrated learning path |
| Separate AI repository | AI is most useful here when applied directly to networking, security, operations, and evidence validation |

## Consequences

This structure improves navigation but requires consistent lab naming and careful placement. Every new lab should be added to the correct topic folder.

Cybersecurity labs must remain defensive, educational, and evidence-based. They should focus on secure configuration, validation, monitoring, incident response, and risk reduction.

AI-assisted labs must record how AI was used and how its output was validated. AI output should be treated as a hypothesis until confirmed by primary evidence.

## Future changes

Additional topic folders may be added if the path expands into specialist areas such as cloud networking, wireless, service provider networking, digital forensics, security engineering, MLOps, or AI observability.