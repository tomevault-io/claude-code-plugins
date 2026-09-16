# meta

> This is a **meta-repo** — a workspace of independent git repositories managed by the `meta` CLI tool. Each directory listed in `.meta` (the project config) is a **separate git repo** with its own remote, commits, and history. NEVER treat this as a monorepo. New crates must be separate git repos added to `.meta` and `.gitignore`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/meta/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Project Architecture: Meta-Repo (NOT a monorepo)

This is a **meta-repo** — a workspace of independent git repositories managed by the `meta` CLI tool. Each directory listed in `.meta` (the project config) is a **separate git repo** with its own remote, commits, and history. NEVER treat this as a monorepo. New crates must be separate git repos added to `.meta` and `.gitignore`.

READ .kb/AGENTS.md

---
> Source: [gitkb/meta](https://github.com/gitkb/meta) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-16 -->
