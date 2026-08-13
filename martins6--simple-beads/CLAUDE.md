# simple-beads

> This repo is about a lightweight, local-first task management CLI. Store tasks in SQLite with support for parent-child relationships, dependencies, and priorities.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/simple-beads/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Simple Beads (sb)

This repo is about a lightweight, local-first task management CLI. Store tasks in SQLite with support for parent-child relationships, dependencies, and priorities.

## Core Tech

- **Go** - CLI built with Cobra framework
- **SQLite** - Local storage with WAL mode for multi-process safety
- **Architecture** - Standard Go project structure (`cmd/`, `internal/`)

## Quick Start of sb commands

```bash
sb init                    # Initialize in current directory
sb create "Fix bug"        # Create a task
sb ready                   # See tasks ready to work on
sb close <id>              # Mark task as done
```

## Data Location

Tasks stored in `.sbeads/tasks.db` (SQLite database).

---
> Source: [Martins6/simple-beads](https://github.com/Martins6/simple-beads) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
