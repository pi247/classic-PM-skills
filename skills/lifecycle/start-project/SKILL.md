---
name: start-project
description: >
  Orchestrate project initiation: context, stress-test alignment, charter and
  stakeholders, through a ready-to-plan gate. Use when kicking off a project or
  authorizing work.
license: MIT
metadata:
  classic-pm.pack: classic-pm-skills
  classic-pm.version: "1.0"
  classic-pm.artifact: none
  classic-pm.level: project
---

# Start project

Orchestrator - do not duplicate document templates; call the specialist skills.

## Sequence

1. Ensure setup (`.classic-pm/`) exists or run `setup-classic-pm`.
2. Ensure `ORG_CONTEXT.md` / `PROJECT_CONTEXT.md` exist; fill via `org-context` / `project-context` as needed.
3. `/stress-test` until initiation assumptions are aligned (docs mode recommended).
4. `draft-project-charter` then `draft-stakeholder-register`.
5. **Ready-to-plan gate:** charter authorized (or clear next approval), stakeholders listed, open assumptions that block planning are closed or explicitly deferred.

Output a short initiation checklist of what is done vs deferred.
