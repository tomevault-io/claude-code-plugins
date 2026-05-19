# ui-shadcn

> Use when building or changing UI. Reuse shadcn/ui primitives and follow design system.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ui-shadcn/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# UI / shadcn

- Prefer delegating to the `frontend` subagent for shadcn/Tailwind UI work.
- Reuse primitives from `resources/js/components/ui`. Do not duplicate; compose or extend.
- New components: build from ui (Button, Card, Dialog, Input, etc.); use `cn()` and CVA where appropriate.
- Icons: lucide-react.
- Reference: components.json (aliases), resources/js/components/ui/button.tsx (CVA + cn pattern).

---
> Source: [andrejvysny/spendly](https://github.com/andrejvysny/spendly) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
