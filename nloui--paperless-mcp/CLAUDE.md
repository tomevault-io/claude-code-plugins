# http-transport

> - The MCP server can run in HTTP mode using the `--http` CLI flag.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/http-transport/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# HTTP Transport Mode for MCP Server

- The MCP server can run in HTTP mode using the `--http` CLI flag.
- When `--http` is set, the entrypoint [src/index.ts](mdc:src/index.ts) starts an Express server and exposes the MCP API at `/mcp`.
- Each POST to `/mcp` creates a new `McpServer` and `StreamableHTTPServerTransport` for stateless, isolated handling.
- The HTTP port can be set with `--port` (default: 3000).
- Express must be installed as a dependency for HTTP mode.
- If `--http` is not set, the server runs in stdio mode as before.

---
> Source: [nloui/paperless-mcp](https://github.com/nloui/paperless-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
