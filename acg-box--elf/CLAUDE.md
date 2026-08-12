# elf

> These instructions define repository-specific execution rules and scope limits for this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/elf/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md — Repository-Specific Rules for Automated Agents

These instructions define repository-specific execution rules and scope limits for this repository.

---

## 1. Execution Model

## 1.1 Workspace Automation (cargo make)

- `Makefile.toml` is the source of truth for task names and behavior.
- Run `cargo make` from the repository root, and use it whenever an equivalent task exists.
- Run standalone commands only when `Makefile.toml` does not cover the capability or cannot produce the required effect for the current task.
- When task details are needed, inspect `Makefile.toml` directly or run `cargo make --list-all-steps`.

---
> Source: [acg-box/ELF](https://github.com/acg-box/ELF) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
