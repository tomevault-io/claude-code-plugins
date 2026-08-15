# repo-context-ledger

> Route Cursor through the repository's verified, cross-Agent context ledger.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/repo-context-ledger/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Read and follow the repository root `AGENTS.md`. Use `python .context-ledger/ledger.py context --query "<task>"` to load the smallest relevant Context Pack and stable spec. Treat Cursor Memory as a private cache, never as the repository source of truth. Run ledger lifecycle commands autonomously; never delegate them to the user. Never message or steer another user-owned task unless the user explicitly requested cross-task coordination.

---
> Source: [gviiisen/repo-context-ledger](https://github.com/gviiisen/repo-context-ledger) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-15 -->
