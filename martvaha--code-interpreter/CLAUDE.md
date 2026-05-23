# global

> Global project rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/global/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Project uses uv and pyproject.toml for deps management
- Install deps with uv sync --all-extras
- After making changes, run `pytest tests -v` or for specific test `pytest tests/{test} -v`
- Check test logs from `logs/test.log`
- After making changes, verify that [endpoints.py](mdc:app/api/endpoints.py) still follows [librechat-code-interpreter-openapi.json](mdc:project/librechat-code-interpreter-openapi.json)

---
> Source: [martvaha/code-interpreter](https://github.com/martvaha/code-interpreter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
