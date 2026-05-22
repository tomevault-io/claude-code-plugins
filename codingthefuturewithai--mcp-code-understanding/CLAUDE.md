# python-formatting-rules

> After any modifications to Python files, automatically run black and isort on the modified files to maintain consistent code formatting.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/python-formatting-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

After any modifications to Python files, automatically run black and isort on the modified files to maintain consistent code formatting.

File pattern matches: *.py

Example:
```bash
black {file}
isort {file}
```

---
> Source: [codingthefuturewithai/mcp-code-understanding](https://github.com/codingthefuturewithai/mcp-code-understanding) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
