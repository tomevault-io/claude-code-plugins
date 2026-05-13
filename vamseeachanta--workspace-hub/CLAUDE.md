# workspace-hub

> > Canonical instructions: AGENTS.md | Docs: `docs/`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/workspace-hub/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Workspace Hub — Gemini Adapter
> Canonical instructions: AGENTS.md | Docs: `docs/`
## Gemini-Specific
- Retrieval first — consult `docs/` for reference maps and domain guides before searching
- Current workflow surface: `AGENTS.md`, `docs/work-queue-workflow.md`, `docs/modules/ai/AGENT_EQUIVALENCE_ARCHITECTURE.md`, and `.gemini/` (older wrapper-based entrypoints are deleted legacy paths)
- Cross-review: `echo content | gemini -p "prompt" -y`
- Gate evidence: use current workflow anchors in `AGENTS.md`, `docs/work-queue-workflow.md`, and `docs/governance/SESSION-GOVERNANCE.md` (older legacy references are redirect-only; see `docs/ops/legacy-claude-reference-map.md`)

---
> Source: [vamseeachanta/workspace-hub](https://github.com/vamseeachanta/workspace-hub) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
