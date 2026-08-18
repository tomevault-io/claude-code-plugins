# git-attribution

> Enforce human-only Git attribution for the nomifun-tauri repository

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-attribution/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Follow the repository-wide rules in `/AGENTS.md`. Every Git author, committer,
and co-author must identify the responsible human. Cursor and every other AI
model or product may assist with changes but must not be credited in commit
identity fields or attribution trailers.

Use `bun run setup:git-hooks` after cloning. Do not change global Git
configuration and do not bypass repository hooks with `--no-verify`.

---
> Source: [nomifun/nomifun-desktop](https://github.com/nomifun/nomifun-desktop) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-18 -->
