# Commit Strategy

## Purpose

This document defines how changes should be recorded in this repository.

The goal is to keep the history readable and easy to review.

## Principles

Changes should be:

- small
- logical
- complete
- descriptive
- easy to review

## When to record a change

Record a change when one logical unit of work is complete.

Examples:

- create the initial repository structure
- add a topic folder README
- add a new lab write-up
- document a troubleshooting decision
- update a completed lab
- fix a specific documentation error

## Message style

Use short, descriptive messages.

Examples:

```text
Create networking lab structure
Add packet flow lab
Document network lab placement rules
Update DNS lab evidence
```

## Review checklist

Before recording a change:

1. Check the repository state.
2. Review changed files.
3. Confirm the change has one clear purpose.
4. Confirm evidence is suitable for the repository.
5. Write a meaningful message.

## Branching rules

Use branches when a change is large, experimental, or needs review.

Suggested branch names:

```text
docs/update-lab-template
lab/add-packet-flow-lab
fix/readme-topic-table
```

For solo learning work, small documentation updates may be added directly to `main`. In a team environment, changes should usually be made through a branch and pull request.