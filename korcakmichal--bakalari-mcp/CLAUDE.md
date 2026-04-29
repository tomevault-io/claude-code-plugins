# bakalari-mcp

> Pythonic code with type hints. Functions/methods in snake_case, classes in PascalCase. Standard library imports first, then third-party. Logging via `logging` module. Exemplified in [server.py](server.py), [client.py](client.py), [formatter.py](formatter.py).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bakalari-mcp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Guidelines

## Code Style
Pythonic code with type hints. Functions/methods in snake_case, classes in PascalCase. Standard library imports first, then third-party. Logging via `logging` module. Exemplified in [server.py](server.py), [client.py](client.py), [formatter.py](formatter.py).

## Architecture
MCP server bridging LLMs and Bakalari API v3. Components: Server (tool registration/orchestration), Client (HTTP requests/auth), Formatter (output beautification). Global Client instance for API access. See [README.md](README.md) for overview.

## Build and Test
- Install: `uv sync`
- Run server: `uv run --env-file=.env server.py`
- Python >=3.13 required. No tests defined—prototype project.

## Conventions
API methods match Bakalari endpoints. Tools prefixed by category. Auth via environment variables (`BK_PWD`, `BK_USER`, `BK_API_BASE`). Decorator for login handling. Table formatting for readable output. Avoid hardcoding credentials. See [client.py](client.py) for auth patterns.

---
> Source: [KorcakMichal/bakalari-mcp](https://github.com/KorcakMichal/bakalari-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-29 -->
