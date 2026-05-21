# general-guidelines

> Please follow these guidelines:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/general-guidelines/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# General Guidelines
Please follow these guidelines:
- all functions should have type hints for parameters and outputs. For built in type hints (like `list`, `dict`, `tuple`) don't import the typing library, just use the more modern type hints built into Python.
- avoid using comments and rather give descriptive function/variable names. Only use comments when absolutely necessary to communicate something you can't infer from the code or mention design decisions.
- Please copy the formatting choices in the file (e.g. don't redistribute lines as these were chosen by black formatter)

---
> Source: [Metaculus/forecasting-tools](https://github.com/Metaculus/forecasting-tools) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
