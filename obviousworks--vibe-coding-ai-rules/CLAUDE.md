# vibe-coding-ai-rules

> - Strict mode with `exactOptionalPropertyTypes`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vibe-coding-ai-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# FocusFlow Code Style

## TypeScript/React
- Strict mode with `exactOptionalPropertyTypes`
- Explicit return types on all functions
- Prefer `type` over `interface`
- Server Components by default; `'use client'` only when needed
- No default exports (except Next.js pages/layouts)
- No `any` — use `unknown` with type guards

## Python
- Type hints required for all functions
- Pydantic for data validation
- Async/await for all I/O
- PEP 8 + Black (line length 88)

## Naming
- Files: `kebab-case.tsx`, `snake_case.py`
- Components: PascalCase
- Functions: camelCase with verb prefixes
- Constants: UPPER_SNAKE_CASE

## Formatting
- 2 spaces (TS), 4 spaces (Python)
- 100 chars (TS), 88 chars (Python)
- Single quotes (TS), double quotes (Python)
- Semicolons required (TS)

## Patterns
- Repository pattern for data access
- Service layer for business logic
- CQRS for analytics
- Atomic design for UI

---
> Source: [obviousworks/vibe-coding-ai-rules](https://github.com/obviousworks/vibe-coding-ai-rules) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
