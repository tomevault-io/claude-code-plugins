# mcp-server-pattern

> Core coding patterns for MCP Server implementation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-server-pattern/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Use the following pattern for MCP server implementation

```python
server = Server("codelogic-mcp-server")

@server.list_tools()
async def handle_list_tools() -> list[types.Tool]:
    # Define and return tools
    
@server.call_tool()
async def handle_call_tool(name: str, arguments: dict | None) -> list[types.TextContent]:
    # Handle tool execution
```

- New tools should be added to `handlers/__init__.py` `handle_list_tools()` with descriptive names (prefix: `codelogic-`)
- Tool handlers should be routed in `handle_call_tool()`
- Create handler functions with proper error handling
- Return results as markdown-formatted text

---
> Source: [lineai-intelligence/codelogic-mcp-server](https://github.com/lineai-intelligence/codelogic-mcp-server) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-04 -->
