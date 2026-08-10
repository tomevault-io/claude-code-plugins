# blitzdenk

> A coding and research Harness written in zig with vendored Lua.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/blitzdenk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Project Blitzdenk

A coding and research Harness written in zig with vendored Lua.

Zig version: 0.16

Important modules:

- `src/main.zig` control flow
- `src/app.zig` main tui state and render
- `src/tui` tui lib and common widgets
- `src/tools` agent tool definitions
- `src/provider` core agent framework
- `src/lua.zig` the lua bindings, big file
- `src/mcp.zig` the mcp api and tools.
- `src/lsp.zig` the lsp api and tools.
- `src/context_factory.zig` agent and prompt configuration
- `src/commands.zig` async command queue.
- `src/inject.zig` agent status injections.

## Commands

- `zig build gen` generate the lua meta file `src/blitz_defs.lua`

## RULES

- Do not write comments!

---
> Source: [Lommix/blitzdenk](https://github.com/Lommix/blitzdenk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
