# data-modeling

> - **Pydantic BaseModel** - Use for all serializable data structures, API schemas, and persistence models

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data-modeling/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Data Modeling and Architecture

- **Pydantic BaseModel** - Use for all serializable data structures, API schemas, and persistence models
- **@dataclass** - Use for lightweight, performance-critical structures (environment tiles, graph nodes)
- **Protocol** - Use for interfaces and abstract contracts
- **Field validation** - Use Pydantic `Field()` for constraints, descriptions, and metadata
- **Type unions** - Use `str | None` syntax for optional fields, not `Optional[str]`

---
> Source: [miniverse-ai/miniverse](https://github.com/miniverse-ai/miniverse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
