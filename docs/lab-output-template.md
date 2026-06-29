# Lab Output Template

Use this template for every networking, cybersecurity, automation, cloud administration, observability, tooling, or AI-assisted operations lab. The learner should focus on solving the lab. Documentation is produced from the learner's evidence, commands, outputs, screenshots/summaries, issues encountered, and answers to seven reflection questions.

Every normal lab must be scoped for a focused 60-90 minute working session.

Every lab has two required parts:

```text
Part 1 - New chapter or lab-specific content
Part 2 - Cumulative repetition of all topics learned so far
```

Every lab must also include controlled break/fix work inside an authorised lab environment.

Every lab should check official online documentation where commands, tools, platforms, APIs, cloud services, vendor features, or SRE practices are involved.

---

# Lab Title

## 1. Lab Summary

**Lab:**

**Estimated duration:** 60-90 minutes maximum

**Date completed:**

**Topic area:**

**Difficulty:**

**Status:** Completed / Partially completed / Blocked

### Objective

State the purpose of the lab in 2-4 lines.

---

## 2. Scenario

Describe the real-world situation this lab simulates.

The scenario should explain the role, team or organisation, affected service or users, trigger for the work, and why the work matters.

---

## 3. Reference Material

List the full chapters or full relevant chapter sections used for the lab.

| Area | Full reference chapter or full relevant section |
| --- | --- |
| Primary `Computer Networks` chapter | |
| Socket programming | |
| Automation | |
| Cybersecurity | |
| AI-assisted operations | |
| Operations / sysadmin practice | |
| Cloud administration practice | |

Reference rule: when a lab references a book chapter, use the full assigned chapter as the reference unit, not isolated fragments.

---

## 4. Online Documentation Checked

Record official online documentation checked for current command, tool, platform, API, vendor, cloud, or SRE behaviour.

| Documentation | Why checked | Date checked | Version or scope note |
| --- | --- | --- | --- |
| | | YYYY-MM-DD | |
| | | YYYY-MM-DD | |

---

## 5. Requirements

| ID | Requirement | Status |
| --- | --- | --- |
| R1 | Confirm the lab is scoped for 60-90 minutes maximum | Not started / Passed / Failed / Partial |
| R2 | Complete Part 1 new content task | Not started / Passed / Failed / Partial |
| R3 | Complete Part 2 cumulative repetition task | Not started / Passed / Failed / Partial |
| R4 | Introduce a controlled break/fix failure | Not started / Passed / Failed / Partial |
| R5 | Diagnose, fix, and validate recovery | Not started / Passed / Failed / Partial |
| R6 | Check relevant official online documentation | Not started / Passed / Failed / Partial |
| R7 | Capture verification evidence for both parts | Not started / Passed / Failed / Partial |

---

## 6. Constraints

List anything the lab was not allowed to do.

Break/fix work must stay inside an authorised lab environment.

If the core lab begins to exceed 90 minutes, reduce scope rather than expanding the lab.

---

## 7. Assumptions

Record assumptions made before or during the lab.

---

## 8. Expected Structure

Show the expected files and folders for the lab.

```text
example-topic-folder/
└── lab-xx-example-lab.md
```

---

## 9. Deliverables

| File or output | Purpose |
| --- | --- |
| Part 1 evidence | Proves the new content task was completed |
| Part 2 cumulative evidence | Proves previous topics were repeated and applied |
| Break/fix evidence | Proves the learner broke, diagnosed, fixed, and validated recovery |
| Documentation check evidence | Proves current official documentation was checked where relevant |

---

## 10. Implementation Tasks

Record the required tasks and the outcome of each task. This section should document what was solved, not provide a copy-paste walkthrough.

### Part 1 - New chapter or lab-specific content

Describe the new content task, required outcome, and final result.

### Part 2 - Cumulative repetition of all topics learned so far

Describe the cumulative repetition task, the topics repeated, required outcome, and final result.

Part 2 must apply all topics learned so far, including the current lab. It should produce evidence, not just written recall.

---

## 11. Break/Fix Record

Every lab must include a controlled failure and recovery.

| Stage | Notes / evidence |
| --- | --- |
| Expected healthy state | |
| Controlled failure introduced | |
| Symptoms observed | |
| Initial hypothesis | |
| Diagnostic checks performed | |
| Evidence collected | |
| Root cause or likely cause | |
| Fix applied | |
| Recovery validation | |
| Prevention / monitoring / runbook improvement | |

---

## 12. Key Commands Used

| Command | Purpose | Part | Official doc checked? |
| --- | --- | --- | --- |
| | | Part 1 / Part 2 / Break-fix | Yes / No / Not applicable |
| | | Part 1 / Part 2 / Break-fix | Yes / No / Not applicable |

---

## 13. Files Created or Changed

| Path | Purpose | Part |
| --- | --- | --- |
| | | Part 1 / Part 2 / Break-fix |
| | | Part 1 / Part 2 / Break-fix |

---

## 14. Verification Evidence

This section proves the lab worked.

| Check | Evidence | Result | Part |
| --- | --- | --- | --- |
| | | Passed / Failed | Part 1 |
| | | Passed / Failed | Part 2 |
| | | Passed / Failed | Break-fix recovery |

---

## 15. Cumulative Repetition Coverage

List the topics repeated in Part 2.

| Previous topic | How it was repeated | Evidence |
| --- | --- | --- |
| Layering / packet flow | | |
| Physical / link / LAN concepts | | |
| IP addressing / routing / NAT | | |
| Transport / sockets / service exposure | | |
| DNS / HTTP / TLS / application dependency | | |
| Security / firewall / monitoring | | |
| Automation / source of truth / observability | | |

Remove rows that are not yet applicable for early labs.

---

## 16. Diagram

Use this section for network diagrams, traffic-flow diagrams, architecture diagrams, monitoring flows, AI-assisted analysis flows, source-of-truth models, firewall zone models, break/fix flows, or failure/recovery flows.

```mermaid
flowchart LR
    A[Healthy State] --> B[Controlled Failure]
    B --> C[Diagnosis]
    C --> D[Fix]
    D --> E[Validation]
```

---

## 17. Issues Encountered

| Issue | Cause | Fix | Part |
| --- | --- | --- | --- |
| | | | Part 1 / Part 2 / Break-fix |

If there were no issues, write:

> No major issues encountered.

---

## 18. Decisions Made

| Decision | Reason | Part |
| --- | --- | --- |
| | | Part 1 / Part 2 / Break-fix |
| | | Part 1 / Part 2 / Break-fix |

---

## 19. Security and Production Considerations

Explain the production relevance of this lab.

Cover operational risk, access control, firewall policy, segmentation, rollback, audit trail, monitoring, repeatability, documentation, reliability, cost, cloud/admin impact, break/fix safety, and AI risk where relevant.

---

## 20. Tooling, Observability, and Source-of-Truth Notes

Complete this section when relevant.

| Area | Notes |
| --- | --- |
| Current tooling | |
| Tooling gap | |
| Monitoring / alerting | |
| Logs / packet evidence | |
| CMDB or source-of-truth impact | |
| Automation opportunity | |
| Break/fix detection opportunity | |

---

## 21. AI Usage and Validation

Complete this section if AI was used.

| AI use | Output produced | How it was validated | Result | Part |
| --- | --- | --- | --- | --- |
| | | | Useful / Incorrect / Incomplete / Not used | Part 1 / Part 2 / Break-fix |

If AI was not used, write:

> AI was not used in this lab.

---

## 22. Final Outcome

State clearly whether Part 1, Part 2, break/fix recovery, and documentation checks were completed.

---

## 23. What I Learned

Summarise the main learning points from the lab and the learner's reflection answers.

- 
- 
- 

---

## 24. What I Would Improve in Production

Summarise the production improvements from the lab and the learner's reflection answers.

- 
- 

---

## 25. References Used

| Reference | Used for |
| --- | --- |
| | |
| | |

---

## 26. Completion Checklist

- [ ] Requirements understood
- [ ] Lab scoped for 60-90 minutes maximum
- [ ] Full assigned chapter or reference section reviewed
- [ ] Relevant official online documentation checked
- [ ] Part 1 new content completed
- [ ] Part 2 cumulative repetition completed
- [ ] Controlled failure introduced safely
- [ ] Break/fix diagnosis completed
- [ ] Fix applied and recovery validated
- [ ] Verification evidence captured for both parts and recovery
- [ ] Issues documented
- [ ] Decisions documented
- [ ] Cumulative repetition coverage documented
- [ ] Security and production considerations documented
- [ ] Tooling, observability, and source-of-truth notes included where relevant
- [ ] AI usage documented if relevant
- [ ] Seven reflection questions answered
- [ ] Diagram added if useful
- [ ] File uploaded to the correct topic folder
- [ ] Evidence reviewed before publishing

---

## 27. Reflection Questions

Ask exactly seven reflection questions after the learner has completed the practical work. The learner answers the questions; the answers are then incorporated into the final uploaded lab document.

1. What problem did Part 1 of this lab simulate, and what new concept did it introduce?
2. What earlier topics did Part 2 force you to repeat, and which one felt weakest?
3. What did you break, what symptoms appeared, and what evidence proved the fix worked?
4. Which official online documentation did you check, and what did it clarify or correct?
5. What would you monitor, log, or alert on in production to catch this failure earlier?
6. What would you improve if this were a real production environment?
7. What did you learn from this lab that you could explain to another engineer?
