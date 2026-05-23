# scripts

> SSH into individual nodes to use available utility scripts:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/scripts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


SSH into individual nodes to use available utility scripts:
- `scripts/mcp_run.sh` - Run the MCP server (node is automatically determined)
- `scripts/setup_env.sh` - Environment setup and activation
- `scripts/lint.sh` - Code linting and formatting
- `scripts/kill.sh` - Clean shutdown of running processes

Logs for the MCP servers are located in `/nfs/mcp-logs/<NODE_NAME>.log`

---
> Source: [hu-po/tatbot](https://github.com/hu-po/tatbot) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
