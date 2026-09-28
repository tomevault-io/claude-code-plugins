# jarvis

> - Never write unit tests after you write code.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/jarvis/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Testing rules

- Never write unit tests after you write code.
- Highly prefer E2E tests as the sole testing mechanism. Use them to verify complex features work. At the end of E2E tests, produce a verifiable and repeatable artifact.
- If you must test a system in isolation, first write down all the ways it could fail, then write the code.

---
> Source: [tranvictor/jarvis](https://github.com/tranvictor/jarvis) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-27 -->
