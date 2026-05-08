# gm-cc

> Hook response format: `{"decision":"allow|block","reason":"text"}` with exit code 0.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gm-cc/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

## Technical Notes

Hook response format: `{"decision":"allow|block","reason":"text"}` with exit code 0.

Tool names for this platform: `bash` → `Bash`, `write` → `Write`, `glob` → `Glob`, `grep` → `Grep`, `search` → `Search`

When filtering transcript history by sessionId, use: `if (sessionId && entry.sessionId === sessionId)`

Verification file `.gm-stop-verified` is auto-added to .gitignore and tracks session completion state.

---
> Source: [AnEntrypoint/gm-cc](https://github.com/AnEntrypoint/gm-cc) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
