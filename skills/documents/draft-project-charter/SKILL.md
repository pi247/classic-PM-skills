---
name: draft-project-charter
description: >
  Draft or revise a project charter (authorization, objectives, high-level
  scope, success criteria). Use when starting a project, authorizing work, or
  the user asks for a charter.
license: MIT
metadata:
  classic-pm.pack: classic-pm-skills
  classic-pm.version: "1.0"
  classic-pm.artifact: charter
  classic-pm.level: project
---

# Draft project charter

Produce or revise a **project charter** as a portable markdown document.

## Before drafting

1. Read `PROJECT_CONTEXT.md` (and `ORG_CONTEXT.md` if present).
2. If open assumptions block authorization, stop and run `/stress-test` first.
3. Prefer facts from context over invention; mark gaps explicitly.

## Template

Use `assets/charter.md`. Skeleton:

## Charter skeleton

```markdown
# Project charter — <name>

## Authorization
- Sponsor:
- Project manager authority:

## Purpose and objectives

## High-level scope
### In scope
### Out of scope

## Success criteria

## Key stakeholders (summary)

## High-level risks and constraints

## Approval
- Authorized by:
- Date:
```

## Rules

- Stay PM-native. Do not invent developer-pack framing.
- Align wording with org/project shared vocabulary.
- After material charter changes, offer to sync `PROJECT_CONTEXT.md` identity/success sections.
