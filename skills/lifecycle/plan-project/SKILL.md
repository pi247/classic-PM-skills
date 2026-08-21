---
name: plan-project
description: >
  Orchestrate planning: scope, WBS, risk, and a light project management plan
  integration. Use when moving from initiation into a usable plan baseline.
license: MIT
metadata:
  classic-pm.pack: classic-pm-skills
  classic-pm.version: "1.0"
  classic-pm.artifact: none
  classic-pm.level: project
---

# Plan project

Orchestrator - specialist skills own templates.

## Sequence

1. Confirm initiation gate (or run `start-project` gaps first).
2. `draft-scope-statement` → `draft-wbs` → `draft-risk-register`.
3. Produce/update a **project management plan** outline (integration output): how we execute, monitor, control, and close - referencing the documents above. Store path per `.classic-pm/paths.md`.
4. Offer `/stress-test` before baselining.

Do not invent schedule/cost deep-dives beyond light placeholders in v1.
