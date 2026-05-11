# pet-peeves

> - If creating a data class, use Pydantic BaseModel, not python data classes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pet-peeves/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- If creating a data class, use Pydantic BaseModel, not python data classes.
- Do not add any comments to the code, unless essential or if the code is particularly obscure. Code should be self documenting. Only doc strings (google doc) are allowed.
- Keep __init__.py files empty, always import modules from package root (dir containing package).
- Do not use singletons.

---
> Source: [rick12000/vocalance](https://github.com/rick12000/vocalance) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
