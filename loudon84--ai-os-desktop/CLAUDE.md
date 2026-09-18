# 002-renderer-ui

> React renderer UI stack, structure, and async panel conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/002-renderer-ui/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Renderer UI Rules

## Stack

- React 19
- TypeScript
- Tailwind CSS 4
- lucide-react icons
- No direct Node.js access

## UI conventions

- Use screen-level components under `src/renderer/src/screens/`
- Use feature components under `src/renderer/src/components/`
- Keep components small and composable.
- Separate data loading hooks from presentational components.
- Every async panel must implement:
  - loading state
  - empty state
  - error state
  - retry action

## Layout conventions

- Desktop-first layout.
- Left navigation width: 240–280px.
- Main content max width for forms: 960–1120px.
- Use card/grid layout for dashboard screens.
- Avoid full-page unstructured forms.
- Avoid nested scroll areas unless explicitly required.

---
> Source: [loudon84/ai-os-desktop](https://github.com/loudon84/ai-os-desktop) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-18 -->
