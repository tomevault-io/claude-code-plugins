# unit-tests

> proper way to run unit tests (parallel by default)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/unit-tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Preferred runner is pytest with xdist for parallel execution. Use the project venv via uv.

- Parallel run (default): `uv run pytest -q -n auto tests |& tee >(tail -n 30) >/dev/null`
- Filter to specific tests: `uv run pytest -q -n auto -k "substring_or_expr" tests`
- Serial fallback (rare): `uv run -m unittest -v -s ./tests -p "test_*.py" -t . |& tee >(tail -n 30) >/dev/null`

---
> Source: [maxim-saplin/llm_chess](https://github.com/maxim-saplin/llm_chess) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
