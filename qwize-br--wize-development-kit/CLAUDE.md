# wize-create-skill

> workflow: Create Skill

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wize-create-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Create Skill

# Create Skill

**Goal.** Scaffold a single-step skill in `.wize/custom/skills/{code}/`.

## Inputs (interactive)
- `code`, `name`, `description`
- `owner` (which agent owns this skill)
- `inputs[]`, `outputs[]`
- `body` (the actual skill content / prompt template)

## Outputs
- `.wize/custom/skills/{code}/skill.md`
- IDE adapter regeneration.

## Validation
- Schema (`schemas/skill.schema.json`).
- Markdown lint.
- Dry-run with stub input.

---
> Source: [qwize-br/wize-development-kit](https://github.com/qwize-br/wize-development-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
