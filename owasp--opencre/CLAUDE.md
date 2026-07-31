# opencre

> Require all-caps confirmation for destructive production DB operations and prefer pre-op backups

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/opencre/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Production DB Operations Safety

- For production database operations, treat destructive actions (`DELETE`, `DROP`, `TRUNCATE`, irreversible `ALTER`) as high risk.
- Prefer using `scripts/db/` operations instead of ad-hoc production DB commands whenever those scripts cover the use case.
- Before proposing or executing destructive production DB actions, require explicit all-caps confirmation from the user.
- Confirmation should be exact and unambiguous (for OpenCRE scripts: `I_UNDERSTAND_OPENCREORG_PROD_DB_DESTRUCTIVE_ACTION`).
- Prefer capturing a fresh backup before destructive production DB actions; if a backup is skipped, clearly explain risk and ask for confirmation again.
- If app/environment target is ambiguous, stop and ask to confirm target app first.

---
> Source: [OWASP/OpenCRE](https://github.com/OWASP/OpenCRE) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
