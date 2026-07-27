# wize-create-workflow

> workflow: Create Workflow

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wize-create-workflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Create Workflow

# Create Workflow

**Goal.** Scaffold a multi-step workflow in `.wize/custom/workflows/{code}/`.

## Inputs (interactive)
- `code`, `name`, `description`
- `owner` (agent)
- `phase` (1-analysis | 2-plan | 3-solutioning | 4-implementation | transversal)
- `steps[]` (numbered list, each with name + brief)
- `inputs[]`, `outputs[]`

## Outputs
- `.wize/custom/workflows/{code}/workflow.md`
- IDE adapter regeneration.

## Validation
- Schema (`schemas/workflow.schema.json`).
- Markdown lint.
- Dry-run: parse steps; render and assert each step has a clear action.

---
> Source: [qwize-br/wize-development-kit](https://github.com/qwize-br/wize-development-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
