---
name: stress-test
description: >
  Run a structured decision walkthrough that surfaces every open assumption and
  dependency in rounds until the plan is fully aligned - before you commit
  resources or baseline. Use when starting or reshaping a project, clarifying
  scope, or the user invokes /stress-test.
license: MIT
metadata:
  classic-pm.pack: classic-pm-skills
  classic-pm.version: "1.0"
  classic-pm.artifact: none
  classic-pm.level: both
---

# Stress-test

Stress-test is a structured decision walkthrough. It surfaces every open assumption and dependency in rounds until the plan is fully aligned - before you commit resources or baseline.

## Modes

1. **Walkthrough only** - sharpen decisions; do not write context files.
2. **Walkthrough and update documents** - same rounds; also update `ORG_CONTEXT.md` / `PROJECT_CONTEXT.md` and append or bridge the Decision Log as answers land.

Default: ask which mode if unclear. One slash entry: `/stress-test`.

## How to run

1. Read existing org/project context (and Decision Log) if present.
2. Build the set of **open assumptions and dependencies**.
3. Ask the whole ready set in one **round**. Number each question. Attach a **recommended** answer to each.
4. Wait for the user’s answers before the next round.
5. Stop when nothing material remains open - the plan is aligned for baseline.

## Language (required)

| Use | Do not use |
| --- | --- |
| round | frontier |
| open assumptions and dependencies | grill / grilling / grill-me |
| recommended | BBQ / cooking metaphors |
| document | developer-pack provenance |

## Outputs

- Clarified decisions (and optionally updated context documents + Decision Log entries).
- Explicit list of what is now aligned vs still deferred.
