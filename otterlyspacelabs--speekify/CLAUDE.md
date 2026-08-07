# speekify

> Speekify is a Python 3.11+ CLI that converts inline text, piped stdin, or readable URL content into a local WAV file using Supertonic v3.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/speekify/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Speekify is a Python 3.11+ CLI that converts inline text, piped stdin, or readable URL content into a local WAV file using Supertonic v3.

Use `uv` for local work. Core checks are `uv sync --group dev`, `uv run pytest`, and `uv run ruff check .`.

The installed command is `speekify`, wired by `pyproject.toml` to `speekify.__main__:main`.

## More Guidance

- [Project architecture](docs/agents/project-architecture.md)
- [Development commands](docs/agents/development-commands.md)
- [Codebase conventions](docs/agents/codebase-conventions.md)
- [Testing patterns](docs/agents/testing-patterns.md)
- [Dependencies and integrations](docs/agents/dependencies-integrations.md)
- [MCP client setup](docs/mcp-clients.md)
- [Release runbook](docs/agents/release-runbook.md)
- [Deletion candidates](docs/agents/deletion-candidates.md)

---
> Source: [OtterlySpaceLabs/speekify](https://github.com/OtterlySpaceLabs/speekify) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-02 -->
