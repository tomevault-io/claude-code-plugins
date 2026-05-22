# avoid-using-dboperations-table

> When interacting with the database, do not try to add a new method to the DbOperations class. This is because the DbOperations class is deprectaed.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/avoid-using-dboperations-table/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When interacting with the database, do not try to add a new method to the DbOperations class. This is because the DbOperations class is deprectaed.

Instead, the functions / methods in the service layer should perform database requests directly.

---
> Source: [Government-Communication-Service/assist_service](https://github.com/Government-Communication-Service/assist_service) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
