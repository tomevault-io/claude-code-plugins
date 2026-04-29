# skills

> Guidelines for AI agents contributing to this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Guidelines for AI agents contributing to this repository.

## Skill structure

Each skill lives in its own directory with a `SKILL.md` inside:

```
<skill-name>/SKILL.md
```

## SKILL.md rules

- YAML frontmatter is required: `name` and `description`
- `name` **must match the directory name** exactly (lowercase alphanumeric, hyphens allowed)
- `description` is 1–1024 characters; write it as a trigger signal — "use this when..."
- Keep content **concise and directive** — no code examples unless essential
- **Do not duplicate upstream docs** — link to them instead. Skills should direct the agent, not replicate reference material
- When adding a skill, add it to the table in `README.md`

---
> Source: [juspay/skills](https://github.com/juspay/skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
