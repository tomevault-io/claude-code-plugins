# ship-status-dev

> MCP server (ship-status-dev) for AI-callable dev tasks

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ship-status-dev/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Shared MCP server for AI-callable dev tasks (migrate, serve, test, monitor). Configuration and tools are in `ship-status-dev/server.py`.

When adding or modifying MCP tools, follow existing patterns in `ship-status-dev/server.py` (`_run_script_background`, `_run_foreground`, `_find_pids`, `_ensure_dev_log_dir`). Restart the MCP server after changes.

Dashboard API tools for agents live in the separate **`ship-status`** MCP (`mcp/`).

---
> Source: [openshift-eng/ship-status-dash](https://github.com/openshift-eng/ship-status-dash) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-08 -->
