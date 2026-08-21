---
name: setup-classic-pm
description: >
  Configure Classic PM Skills for this workspace: tool surface, status vocabularies,
document and context paths, and optional light process notes. Use once when adopting
the pack or when paths/tools change.
license: MIT
metadata:
  classic-pm.pack: classic-pm-skills
  classic-pm.version: "1.0"
  classic-pm.artifact: none
  classic-pm.level: both
---

# Setup Classic PM Skills

Create or update **tool-agnostic** config under `.classic-pm/` so every skill knows where documents live and which vocabulary to use.

## Create

```text
.classic-pm/
  config.md       # tool surface
  vocabularies.md # statuses/labels
  paths.md        # context + document locations
  process.md      # optional predictive / hybrid notes
```

See `examples/.classic-pm/` in this repo for starters.

## Rules

1. Default tool surface: `local-markdown`.
2. Skills read paths from config — never hardcode a vendor UI.
3. Deep Jira/ADO/Asana/Notion/MS Project connectors are out of v1 unless paths + vocabularies are enough.
4. After setup, offer to create empty `ORG_CONTEXT.md` / `PROJECT_CONTEXT.md` / `DECISIONS.md` at the configured paths.
