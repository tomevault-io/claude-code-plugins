# intentra

> CLI layer rules and UX requirements

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/intentra/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# CLI Layer Rules

- No business logic in `cmd/`; delegate to engine packages.
- `plan` prints a readable summary by default.
- `--json` outputs exact CommitPlan JSON.
- `apply` defaults to `--dry-run` unless user passes `--yes` or `--apply`.
- Always print what will happen before doing it.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/crvgilbertson) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
