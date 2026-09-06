# blackscholes

> See [AGENTS.md](AGENTS.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/blackscholes/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# blackscholes

See [AGENTS.md](AGENTS.md).

Python 3.10+, `uv`, `src/` layout. Zero published deps — formulas use stdlib `math`.

```
uv sync --extra dev
uv run ruff format && uv run ruff check && uv run pytest -s
```

---
> Source: [CarloLepelaars/blackscholes](https://github.com/CarloLepelaars/blackscholes) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-06 -->
