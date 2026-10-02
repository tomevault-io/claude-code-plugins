# skills

> This repo is the promotion path for generally useful, public-safe agent skills.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# joelhooks/skills

This repo is the promotion path for generally useful, public-safe agent skills.

## Rules

- No secrets, private machine paths, raw transcripts, customer data, or paid/private corpus text.
- Skills here must be portable: avoid assuming Joel's local Brain, pi-notes, Panda, gateway, or dotfiles exist.
- If a workflow needs private/operator behavior, keep that adaptation in `joelhooks/dark-wizard/skills` and link this repo as a basis.
- Use `skills/<name>/SKILL.md`; directory name and frontmatter `name` must match.
- Keep `SKILL.md` short. Put large examples or references under the skill directory only when they are reusable and public-safe.
- Prefer small governance/process skills that improve agent behavior across projects over one-off project playbooks.

---
> Source: [joelhooks/skills](https://github.com/joelhooks/skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
