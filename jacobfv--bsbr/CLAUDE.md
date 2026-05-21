# run-python-and-pip-using-uv

> We package using `uv`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/run-python-and-pip-using-uv/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

We package using `uv`

- instead of `pip install <package>` run `uv add <package>`
- work inside the venv.
    - create a venv with `uv venv`
    - activate it with `.\.venv\Scripts\activate`
    - always activate before running a python command. the env might not persist between code runs so activate every time you execute commands
- instead of running python packages like `<module> <args>`, run them either using `uvx <module> <args>` or if in a venv, then be sure you activate the venv before running your command

---
> Source: [JacobFV/bsbr](https://github.com/JacobFV/bsbr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
