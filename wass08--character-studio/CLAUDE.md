# character-studio

> Config block read by the engineering skills (`to-issues`, `triage`, `tdd`, `diagnose`, etc.).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/character-studio/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# character-studio

## Agent skills

Config block read by the engineering skills (`to-issues`, `triage`, `tdd`, `diagnose`, etc.).

- **Issue tracker:** GitHub Issues at [`wass08/character-studio`](https://github.com/wass08/character-studio/issues). Skills create/read via `gh issue ...`.
- **Triage labels** (role → label string):
  - `needs-triage` → `needs-triage`
  - `needs-info` → `needs-info`
  - `ready-for-agent` → `ready-for-agent`
  - `ready-for-human` → `ready-for-human`
  - `wontfix` → `wontfix`
- **Glossary:** `docs/agents/glossary.md`
- **ADRs:** `docs/adr/`

> Labels above must exist in the GitHub repo. If `gh label list` doesn't show them, create with `gh label create <name>`.

---
> Source: [wass08/character-studio](https://github.com/wass08/character-studio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-22 -->
