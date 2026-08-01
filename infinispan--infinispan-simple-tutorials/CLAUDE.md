# infinispan-simple-tutorials

> This project connects to an Infinispan server via the MCP stdio transport bridge.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/infinispan-simple-tutorials/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This project connects to an Infinispan server via the MCP stdio transport bridge.

Always use the Infinispan MCP server tools to interact with Infinispan (manage caches, counters, schemas, entries).
Do not use curl or the REST API directly. The MCP server is the intended interface.

The Infinispan MCP server is configured in `.mcp.json` using the CLI stdio bridge (via `docker exec`) and provides tools for:
- Cache operations (create, list, get, put, remove, query)
- Counter operations (get, increment, decrement)
- Schema management

Server credentials: admin / password

---
> Source: [infinispan/infinispan-simple-tutorials](https://github.com/infinispan/infinispan-simple-tutorials) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
