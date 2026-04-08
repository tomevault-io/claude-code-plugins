# pdf-agent

> uv run pytest {Path to the specific unit test} -v

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pdf-agent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Setup
uv sync

## Unit Tests
uv run pytest {Path to the specific unit test} -v

## Integration Tests
uv run pytest {Path to the specific integration test} -v

## Lint
uv run ruff check . --fix && uv run ruff format .

## Rules
- Do NOT edit migrations
- Do NOT change terraform files
- Never commit secrets
- Prefer minimal diffs

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/huangrao121)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/huangrao121)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
