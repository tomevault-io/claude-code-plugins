# constructs

> Before pushing changes, run the full CI pipeline locally to avoid PR failures:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/constructs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

## Pre-push checklist

Before pushing changes, run the full CI pipeline locally to avoid PR failures:

```bash
npm run build && npm run lint && npm run format:check && npm test
```

If `format:check` fails, fix with `npm run format` then re-run the check.

---
> Source: [kirodotdev-labs/constructs](https://github.com/kirodotdev-labs/constructs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-15 -->
