# Networking Lab Output Template

Use this template for every networking lab. Keep it evidence-based, operational, and production-focused.

---

# Lab Title

## 1. Lab Summary

**Lab:**  
**Date completed:**  
**Topic area:**  
**Difficulty:**  
**Status:** Completed / Partially completed / Blocked

### Objective

State the purpose of the lab in 2–4 lines.

---

## 2. Scenario

Describe the real-world networking situation this lab simulates.

A good scenario should explain:

- who is affected
- what system or network path is involved
- what evidence is initially available
- what outcome is required

---

## 3. Reference Material

List the references actually used.

| Area | Suggested reference |
| --- | --- |
| Network theory | Computer Networks / Computer Networking: A Top-Down Approach |
| Socket behaviour | Beej's Guide to Network Programming |
| Automation | Network Programmability and Automation |
| Operational practice | The Practice of System and Network Administration |
| Linux troubleshooting | Linux man pages and distribution documentation |

---

## 4. Requirements

| ID | Requirement | Status |
| --- | --- | --- |
| R1 |  | Not started |
| R2 |  | Not started |
| R3 |  | Not started |

---

## 5. Constraints

Record what must not be done.

Common constraints:

- Do not use company/private data.
- Do not commit secrets, private keys, credentials, packet captures containing sensitive data, or screenshots with private information.
- Do not use copyrighted book PDFs or EPUBs in the repository.
- Do not skip verification evidence.
- Do not mark a lab complete unless the final state is reproducible.

---

## 6. Assumptions

Record your assumptions here.

Examples:

- This is a solo learning lab.
- The environment is isolated and non-production.
- The lab is designed for learning and portfolio evidence.
- Packet captures are sanitised or summarised before committing.

---

## 7. Expected Lab Structure

Use a lowercase, numbered, hyphenated file name inside the correct topic folder.

Example:

```text
01-network-foundations/lab-01-packet-flow-linux-network-inspection.md
03-tcp-udp-socket-programming/lab-07-tcp-handshake-and-client-server.md
09-network-programmability-automation/lab-33-yaml-inventory-network-validation.md
```

---

## 8. Deliverables

| Deliverable | Purpose |
| --- | --- |
| Lab write-up | Documents the work, decisions, and evidence |
| Diagram | Shows topology, packet flow, or service dependencies where useful |
| Verification evidence | Proves the lab works |
| Troubleshooting notes | Captures mistakes, symptoms, causes, and fixes |
| Production reflection | Explains how the topic matters in real environments |

---

## 9. Implementation Tasks

Use these tasks as a guide, not as a copy-paste walkthrough.

### Task 1 — Understand the problem

Identify the network path, hosts, ports, protocols, services, and expected behaviour.

### Task 2 — Build or inspect the environment

Create or inspect the relevant topology, interfaces, routes, firewall rules, services, or scripts.

### Task 3 — Generate evidence

Use appropriate tools such as `ip`, `ss`, `ping`, `traceroute`, `dig`, `tcpdump`, Wireshark, Python, Ansible, or device CLI commands.

### Task 4 — Break and diagnose

Introduce or investigate a realistic fault. Record symptoms, hypothesis, tests, root cause, and fix.

### Task 5 — Verify and document

Prove the final state works and document what another engineer would need to know.

---

## 10. Key Commands Used

| Command | Purpose |
| --- | --- |
|  |  |
|  |  |

---

## 11. Files Created or Changed

| Path | Purpose |
| --- | --- |
|  |  |
|  |  |

---

## 12. Verification Evidence

| Check | Evidence | Result |
| --- | --- | --- |
|  |  | Passed / Failed / Partial |
|  |  | Passed / Failed / Partial |

---

## 13. Diagram

Use Mermaid, ASCII, or an image reference if a diagram improves understanding.

If no diagram is required, write:

> No diagram required for this lab.

Example:

```mermaid
flowchart LR
    A[Client] --> B[Default Gateway]
    B --> C[Firewall / Router]
    C --> D[Server]
```

---

## 14. Issues Encountered

| Issue | Cause | Fix |
| --- | --- | --- |
|  |  |  |

If there were no issues, write:

> No major issues encountered.

---

## 15. Decisions Made

| Decision | Reason |
| --- | --- |
|  |  |
|  |  |

---

## 16. Security and Production Considerations

Explain the production relevance of the lab.

Cover where relevant:

- blast radius
- least privilege
- firewall policy
- logging and auditability
- packet capture privacy
- change control
- rollback
- monitoring
- documentation quality

---

## 17. Final Outcome

State clearly whether the lab was completed.

---

## 18. What I Learned

Write 3–6 bullet points.

---

## 19. What I Would Improve in Production

Write 2–5 bullet points.

---

## 20. References Used

| Reference | Used for |
| --- | --- |
|  |  |
|  |  |

---

## 21. Completion Checklist

- [ ] Requirements understood
- [ ] Lab placed in the correct topic folder
- [ ] Implementation completed
- [ ] Verification evidence captured
- [ ] Break/fix or troubleshooting section completed
- [ ] Diagram added if useful
- [ ] Decisions documented
- [ ] Security and production considerations documented
- [ ] References listed
- [ ] No secrets, private data, copyrighted books, or unsafe packet captures committed
- [ ] Work committed and pushed to GitHub

---

## 22. Reflection Questions

1. What network behaviour did this lab prove?
2. What evidence confirms the final state works?
3. What broke or could break in production?
4. What commands or tools were most useful?
5. What would you automate next?
6. What would another engineer need to know to support this setup?
