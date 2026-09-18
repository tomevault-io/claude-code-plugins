# 004-layout-quality

> Screen design checklist and UI quality constraints before implementing layouts

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/004-layout-quality/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Layout Quality Rules

Before coding a UI screen, produce:

- Objective
- User workflow
- Information architecture
- Component tree
- Data contract
- State model
- Layout grid
- Responsive behavior
- Empty / loading / error states
- Acceptance checklist

## UI quality constraints

- No placeholder-only UI.
- No fake data unless explicitly marked as mock.
- No giant component over 250 lines.
- No inline business logic in JSX.
- No magic strings for statuses — use typed status enums.
- Use stable spacing scale (Tailwind spacing tokens).
- Every primary action must have disabled / loading / error behavior.

---
> Source: [loudon84/ai-os-desktop](https://github.com/loudon84/ai-os-desktop) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-18 -->
