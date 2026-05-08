# kimi-cli-x

> After writing any Python script, run:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kimi-cli-x/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rules:

After writing any Python script, run:
```bash
uv run tools/syntax_check.py <python_file_name>
```
Fix all errors reported by the syntax checker before proceeding.
use `uv run tools/git_diff.py` to check file diff.

---
> Source: [Sikao-Engine/Kimi-CLI-X](https://github.com/Sikao-Engine/Kimi-CLI-X) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
