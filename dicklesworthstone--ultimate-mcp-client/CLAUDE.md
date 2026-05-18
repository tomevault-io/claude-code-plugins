# 01-project-overview

> The Ultimate MCP Client is a comprehensive client for the Model Context Protocol (MCP) that connects AI models with external tools, servers, and data sources. It provides a powerful interface for managing MCP servers and leveraging their capabilities.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/01-project-overview/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Overview

The Ultimate MCP Client is a comprehensive client for the Model Context Protocol (MCP) that connects AI models with external tools, servers, and data sources. It provides a powerful interface for managing MCP servers and leveraging their capabilities.

## Core Files
- [mcp_client.py](mdc:mcp_client.py) - Main MCP client implementation with CLI, Web UI, and core functionality.
- [mcp_client_multi.py](mdc:mcp_client_multi.py) - Multi-turn version of the MCP client.
- [agent_master_loop.py](mdc:agent_master_loop.py) - Agent Master Loop (AML) implementation for orchestrating AI agents.

## Documentation
- [README.md](mdc:README.md) - Main documentation with features, setup, and usage.
- [AGENT.md](mdc:AGENT.md) - Documentation for the agent implementation.
- [TODO.md](mdc:TODO.md) - Planned improvements and future work.

## Configuration
- [.env-example](mdc:.env-example) - Example environment variables configuration.
- [pyproject.toml](mdc:pyproject.toml) - Project dependencies and configuration.

## Important Features
The Ultimate MCP Client provides:
- Dual interfaces (Web UI and CLI)
- Robust server connectivity (stdio & sse)
- Advanced conversation management with branching
- Powerful tool integration
- Observability via dashboards and telemetry

---
> Source: [Dicklesworthstone/ultimate_mcp_client](https://github.com/Dicklesworthstone/ultimate_mcp_client) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
