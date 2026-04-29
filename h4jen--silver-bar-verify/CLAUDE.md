# silver-bar-verify

> - **NEVER run `git push` without explicit user consent.** Always ask before pushing.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/silver-bar-verify/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## Git Rules

- **NEVER run `git push` without explicit user consent.** Always ask before pushing.
- `git add` and `git commit` are fine without asking, but always confirm before push.

## SSH Rules

- When connecting to the remote server (192.168.66.77), **always use `ssh yspy-server`** (the SSH config alias), never `ssh hajen@192.168.66.77` directly. The alias uses key-based auth and requires no password.

---
> Source: [H4jen/silver-bar-verify](https://github.com/H4jen/silver-bar-verify) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-29 -->
