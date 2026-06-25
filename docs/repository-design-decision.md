# Repository Design Decision

## Context

This repository will contain a sequence of networking and cybersecurity labs covering packet-level fundamentals, Linux troubleshooting, socket programming, routed networks, switching, network services, monitoring, incident response, network automation, secure design, and defensive security operations.

The repository needs to stay understandable as the number of labs grows.

## Decision

Use one repository divided into numbered topic folders. Each folder represents a major networking or defensive security skill area. Individual labs live inside the relevant topic folder.

## Rationale

A single repository presents the labs as one connected learning path. Numbered folders make the learning order obvious. Topic-based folders make it easier to place future labs correctly.

Cybersecurity is included because networking and security are closely linked in real infrastructure work. Network engineers need to understand segmentation, filtering, encryption, identity, logging, monitoring, and defensive evidence handling.

## Folder naming convention

Use lowercase, numbered, hyphenated folder names.

Examples:

```text
01-network-foundations
02-linux-network-troubleshooting
10-cybersecurity-foundations
11-network-security-monitoring-detection
```

## Alternatives considered

| Alternative | Reason it was not chosen |
| --- | --- |
| One repository per lab | Too many repositories and harder to review as a learning path |
| One flat folder | Difficult to navigate once the lab count grows |
| Notes only in the README | The README would become too long |
| Random topic folders | Harder to see progression and maintain consistent placement |
| Separate cybersecurity repository | Security is part of networking and system administration, so separating it would weaken the integrated learning path |

## Consequences

This structure improves navigation but requires consistent lab naming and careful placement. Every new lab should be added to the correct topic folder.

Cybersecurity labs must remain defensive, educational, and evidence-based. They should focus on secure configuration, validation, monitoring, incident response, and risk reduction.

## Future changes

Additional topic folders may be added if the path expands into specialist areas such as cloud networking, wireless, service provider networking, digital forensics, or security engineering.