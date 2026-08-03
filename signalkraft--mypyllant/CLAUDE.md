# mypyllant

> * Use uv for dependency management and executing commands

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mypyllant/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

* Use uv for dependency management and executing commands
* Ensure prek is installed for pre-commit hooks and running tests: `uv run prek install`
* After changing files, run `uv run prek --skip pytest --files ...` for linting and code formatting (drop in for pre-commit)
* When creating a ticket or PR, add a disclaimer that explains what AI was used for in the process

---
> Source: [signalkraft/myPyllant](https://github.com/signalkraft/myPyllant) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
