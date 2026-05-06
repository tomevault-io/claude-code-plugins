# 30-testing

> USE WHEN: adding or changing behavior. Test-first loop.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/30-testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Rules

## Test-First Loop
1. Write failing test
2. Implement until green
3. Refactor (tests stay green)

## Verification
- Run lint → typecheck → tests
- State what’s not run and why

## Guard Clauses
- Prefer early returns to reduce nesting and complexity

---
> Source: [zoxknez/ai-coding-rules](https://github.com/zoxknez/ai-coding-rules) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
