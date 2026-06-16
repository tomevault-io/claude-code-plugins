# ezorm

> Entry point for ezorm repo skills. Use to pick the right skill based on task (write YAML vs generate code, and mongo vs mysql/mysqlr).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ezorm/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Ezorm Skills Index

## Choose a Skill

- Write YAML schema (mongo): `ezorm-write-yaml-mongo`
- Write YAML schema (mysql/mysqlr): `ezorm-write-yaml-mysql` (prefer mysqlr unless explicitly asked for mysql)
- Generate Go from YAML (mongo): `ezorm-gen-yaml-mongo`
- Generate Go from YAML (mysql/mysqlr): `ezorm-gen-yaml-mysql` (prefer mysqlr unless explicitly asked for mysql)

## Notes

- YAML is the source of truth. Generate code with `ezorm gen` using the gen-yaml skills.
- Use db-specific docs and examples referenced inside each skill folder.

---
> Source: [ezbuy/ezorm](https://github.com/ezbuy/ezorm) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
