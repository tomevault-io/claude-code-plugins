# uxnan

> **Single source of truth: [`AGENTS.md`](AGENTS.md).** Keep every rule, convention

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/uxnan/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Uxnan — Gemini CLI entry point

**Single source of truth: [`AGENTS.md`](AGENTS.md).** Keep every rule, convention
and status note there — not here. This file exists only so Gemini CLI loads those
guidelines automatically: Gemini CLI reads `GEMINI.md` as its context file and
resolves the `@`-import below by inlining `AGENTS.md`.

So: write once in `AGENTS.md`; every Gemini CLI session picks up the changes with
no duplication and nothing for you to copy. (Codex and OpenCode read `AGENTS.md`
directly; Claude Code imports it via `CLAUDE.md`.)

@AGENTS.md

---
> Source: [luisgamas/uxnan](https://github.com/luisgamas/uxnan) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-06 -->
