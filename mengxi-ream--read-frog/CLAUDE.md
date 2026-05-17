# read-frog

> - `src/utils/host/translate/api/__tests__/free-api.test.ts` depends on live external translation services.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/read-frog/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Testing Notes

- `src/utils/host/translate/api/__tests__/free-api.test.ts` depends on live external translation services.
- When running tests locally as an AI agent, set `SKIP_FREE_API=true`.
- If `SKIP_FREE_API=true` is set, treat `free-api.test.ts` as intentionally skipped during local validation.

---
> Source: [mengxi-ream/read-frog](https://github.com/mengxi-ream/read-frog) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
