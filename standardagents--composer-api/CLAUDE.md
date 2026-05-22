# composer-api

> - Use Conventional Commits for every commit message: `<type>: <summary>`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/composer-api/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Instructions

- Use Conventional Commits for every commit message: `<type>: <summary>`.
- Keep commit subjects factual and neutral. Prefer wording like `chore: move endpoint configuration to secrets`.
- Do not commit private Cursor backend origins, endpoint paths, or service names. Keep them in Worker secrets or local environment files only.
- Before force-pushing rewritten history, scan all reachable commits for private endpoint strings.

---
> Source: [standardagents/composer-api](https://github.com/standardagents/composer-api) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
