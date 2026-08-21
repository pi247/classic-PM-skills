# Classic PM Skills

MIT agent skills for **classic project management**, written for project managers.

Stress-test is a structured decision walkthrough. It surfaces every open assumption and dependency in rounds until the plan is fully aligned — before you commit resources or baseline.

## Install

Copy or symlink each skill folder into `.agents/skills/<skill-name>/` (flatten category folders):

```bash
# from this repo root
for d in skills/*/*; do
  name=$(basename "$d")
  mkdir -p .agents/skills
  ln -s "$(pwd)/$d" ".agents/skills/$name"  # or cp -R
done
```

Claude Code–only setups may use `.claude/skills/` the same way.

## Skills (v1)

| Skill | When to use |
| --- | --- |
| `setup-classic-pm` | First-time paths, vocabularies, tool surface |
| `org-context` / `project-context` | Shared org or project language |
| `stress-test` | `/stress-test` decision walkthrough (optional update-documents mode) |
| `draft-project-charter` | Authorize the project |
| `draft-stakeholder-register` | Who matters and how to engage |
| `draft-scope-statement` | In/out, deliverables, assumptions |
| `draft-wbs` | Decompose scope |
| `draft-risk-register` | Risks and responses |
| `start-project` | Initiation orchestrator |
| `plan-project` | Planning orchestrator (+ management plan outline) |
| `diagnose-project-health` | Health check |
| `recover-project` | Recovery from a diagnosis |

Portable shapes: [`docs/artifact-contract.md`](docs/artifact-contract.md). Examples: [`examples/`](examples/).

## License

MIT — see [LICENSE](LICENSE).
