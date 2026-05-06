# 62-stack-python

> USE WHEN: working on Python/FastAPI services.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/62-stack-python/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Python / FastAPI

## Typing & Validation
- Use Pydantic v2 models for request/response schemas.
- Avoid raw dicts for external inputs.

## Async
- Use `async def` for I/O‑bound operations.
- Prefer `asyncpg` (or async‑capable drivers) for DB access.

## Style
- Prefer functions over classes unless stateful behavior is required.

---
> Source: [zoxknez/ai-coding-rules](https://github.com/zoxknez/ai-coding-rules) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
