# Networking Cybersecurity and AI Lab Series

## Recommended length

The full programme is designed as 72 challenge-based labs.

The original networking path remains intact, with added cybersecurity and AI-assisted operations phases focused on defensive networking, secure design, monitoring, detection, evidence handling, AI-assisted troubleshooting, and human-verified analysis.

## Phases

| Phase | Labs | Focus |
| --- | ---: | --- |
| 1 | 1-6 | Network foundations and troubleshooting method |
| 2 | 7-14 | TCP, UDP, and socket programming |
| 3 | 15-24 | Routing, switching, segmentation, filtering, and NAT |
| 4 | 25-32 | Network services as production dependencies |
| 5 | 33-42 | Network programmability and automation |
| 6 | 43-48 | Production networking scenarios |
| 7 | 49-56 | Cybersecurity foundations and network security monitoring |
| 8 | 57-64 | AI-assisted networking and security operations |
| 9 | 65-72 | Final integrated capstone scenarios |

## Cybersecurity additions

Cybersecurity labs should focus on defensive skills that naturally extend networking:

- secure network design
- least privilege traffic flow
- segmentation and trust boundaries
- authentication and authorisation concepts
- encryption, TLS, certificates, and PKI
- logging and evidence handling
- defensive packet analysis
- baseline monitoring
- incident triage and response
- hardening and validation

## AI additions

AI labs should focus on practical operational support rather than replacing engineering judgement:

- prompt engineering for technical troubleshooting
- summarising logs, alerts, and packet evidence
- turning troubleshooting notes into runbooks
- generating hypotheses from symptoms
- checking configurations for risk or inconsistency
- comparing AI suggestions against command output
- producing safer incident summaries
- building small AI-assisted helper scripts
- documenting when AI output was useful, wrong, incomplete, or unsafe

## Lab design rule

Labs should be challenge-based rather than walkthrough-based.

Each lab should provide:

- a scenario
- source reading
- requirements
- constraints
- tasks
- verification checks
- operational documentation
- security considerations
- AI-assisted analysis where relevant
- reflection questions

The lab should not provide every answer upfront. The learner should read, test, troubleshoot, use AI carefully where useful, and prove the result.

## Evidence rule

Each completed lab should include enough evidence that another engineer can understand what was built, how it was tested, what failed, what was fixed, what security decisions were made, how AI was used if relevant, and what would be improved in a production environment.

AI output must be validated with primary evidence such as commands, logs, packet captures, configuration, tests, or documentation.