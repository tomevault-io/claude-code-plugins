# error-handling

> Error handling patterns for the CodeLogic MCP Server

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/error-handling/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Use the following pattern for error handling in tool implementations

```python
try:
    # Operations that might fail
except Exception as e:
    sys.stderr.write(f"Error: {str(e)}\n")
    return [types.TextContent(type="text", text=f"# Error\n\n{str(e)}")]
```

- Always catch and report exceptions
- Write errors to stderr
- Return formatted error messages to the client

---
> Source: [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
