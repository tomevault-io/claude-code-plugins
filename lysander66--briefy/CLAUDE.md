# run-commands

> - **必须使用 `uv run`** 来运行 Python 脚本和命令，而不是直接使用 `python` 或 `python3`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/run-commands/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# 运行命令规则

## Python 脚本执行

- **必须使用 `uv run`** 来运行 Python 脚本和命令，而不是直接使用 `python` 或 `python3`
- 例如：
  - `uv run test-aggregator.py`
  - `uv run python -c "..."`
  - `uv run main.py`

---
> Source: [Lysander66/briefy](https://github.com/Lysander66/briefy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-01 -->
