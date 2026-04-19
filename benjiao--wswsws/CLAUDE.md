# wswsws

> Never run migrations unless user explicitly requests

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wswsws/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Migration Execution Policy

- Never run `makemigrations`, `migrate`, or any migration-generation command automatically.
- Never apply database migrations automatically.
- If schema/model changes require migrations, stop and ask the user to run them manually.
- You may mention the exact command(s) the user should run, but do not execute them unless explicitly requested.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/benjiao) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
