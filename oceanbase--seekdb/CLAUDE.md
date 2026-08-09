# seekdb

> - New C++ classes, including interface classes, do not need the legacy `Ob` prefix.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/seekdb/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Agent Guidance

## C++ Type Naming

- New C++ classes, including interface classes, do not need the legacy `Ob` prefix.
- Keep the `I` prefix for interface classes. For example, use `ICacheMemoryGetter` instead of `ObICacheMemoryGetter`.
- Do not rename existing types only to remove the `Ob` prefix unless the task explicitly requires it.

---
> Source: [oceanbase/seekdb](https://github.com/oceanbase/seekdb) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
