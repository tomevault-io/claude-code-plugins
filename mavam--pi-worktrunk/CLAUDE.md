# pi-worktrunk

> `pi-worktrunk` is a pi extension that exposes Worktrunk status, commands, session

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-worktrunk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# pi-worktrunk

`pi-worktrunk` is a pi extension that exposes Worktrunk status, commands, session
continuation, and agent tools.

## Setup

Install Lefthook once per clone:

```bash
uvx lefthook install
```

Pushing runs the quality gates automatically. No need to run checks manually.

## Release engineering

- Use `tenzir-ship` for changelog management and releasing
- Add changelog entries for user facing changes
- Before releasing, ensure `main` is in sync with `origin/main`
- To release, dispatch .github/workflows/release.yaml with a title & intro

---
> Source: [mavam/pi-worktrunk](https://github.com/mavam/pi-worktrunk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
