# llm-conversation

> For complete development setup, code style guidelines, and contribution process, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/llm-conversation/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Development Guidelines

## Development Setup and Guidelines

For complete development setup, code style guidelines, and contribution process, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Key Points for Agents

- **Python version**: 3.13+ only
- **Project structure**: Source in `src/llm_conversation/`, scripts in `scripts/`
- **Documentation**: Always update README.md and docstrings for functional changes. For changes concerning development, update CONTRIBUTING.md instead.
- **Checks**: After major changes, format the code and run all checks with `uv run ruff format && uv run ruff check && uv run ty check`

---
> Source: [famiu/llm_conversation](https://github.com/famiu/llm_conversation) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
