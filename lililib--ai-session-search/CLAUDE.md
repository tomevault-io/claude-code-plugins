# ai-session-search

> - Keep the application read-only with respect to Claude Code and Codex source directories.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-session-search/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Instructions

- Keep the application read-only with respect to Claude Code and Codex source directories.
- Store user-owned metadata only in the application database.
- Do not hardcode user home paths. Preserve CLI, environment, and platform-default precedence.
- Add or update tests before changing provider parsers, indexing, search, rename, or favorite behavior.
- Run `corepack pnpm test`, `corepack pnpm typecheck`, and `corepack pnpm build` before handoff.
- Keep code, comments, and commit messages in English.

---
> Source: [lililib/ai-session-search](https://github.com/lililib/ai-session-search) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
