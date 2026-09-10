# hello-ltr

> - Always use the venv when running python commands.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/hello-ltr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Always use the venv when running python commands.
- Always use uv.
- DO NOT uses pyenv.
- Always use pyproject.toml, not requirements.txt.
- Instead of creating separate documents recording fixes, update the original code issue docs.
- After making any significant change to types, run pyright.
- Whenever providing hard-coded dates (e.g. when a report was updated) check the current date. You usually get it wrong, often by years.
- When running tests, make sure the output is streamed and not just buffered or hidden.
- Always lint a file after editing it.

---
> Source: [o19s/hello-ltr](https://github.com/o19s/hello-ltr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
