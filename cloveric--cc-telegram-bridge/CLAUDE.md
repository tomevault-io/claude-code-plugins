# cc-telegram-bridge

> Before modifying this repository, read [docs/entrypoint-map.md](docs/entrypoint-map.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cc-telegram-bridge/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Entry

Before modifying this repository, read [docs/entrypoint-map.md](docs/entrypoint-map.md).

That file is the source of truth for:
- Telegram entry flow
- bus flow
- state/config ownership
- shared usage/budget/audit logic
- required regression tests by change area

If you change behavior rather than comments/docs, prefer focused tests first, then `npm run build`.

---
> Source: [cloveric/cc-telegram-bridge](https://github.com/cloveric/cc-telegram-bridge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-19 -->
