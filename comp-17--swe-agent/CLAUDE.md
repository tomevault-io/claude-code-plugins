# general

> - Use python with type annotations

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/general/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Your rule content

- Use python with type annotations
- Target python 3.11 or higher
- Use `pathlib` instead of `os.path`. Also use `Path.read_text()` over `with ...open()` constructs
- Use `argparse` to add interfaces
- Keep code comments to a minimum and only highlight particularly logically challenging things
- Do not append to the README unless specifically requested

---
> Source: [comp-17/SWE-Agent](https://github.com/comp-17/SWE-Agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-07 -->
