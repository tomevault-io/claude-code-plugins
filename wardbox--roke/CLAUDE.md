# styling

> Styling and UI/UX Design

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/styling/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Styling

**Description**: Guidelines for styling with Tailwind CSS and component
organization

## Icon library

- Use @phosphor-icons/react for icons

## Tailwind CSS

- Use Tailwind CSS for styling
- Follow semantic color naming (e.g., text-destructive, not text-red-500)
- Let the theme handle colors and spacing
- Follow mobile-first approach
- Use good UI spacing via the tailwind gap class
- Prefer padding over margins

## Component Structure

- Group related styles together
- Use meaningful class names
- Leverage Tailwind's responsive utilities

## Formatting

- Use &apos; for apostrophes in content
- Follow project prettier rules with:
  - No semicolons
  - Single quotes
  - JSX single quotes
  - 2 space indentation
  - No tabs The prettier file is in @file('.prettierrc')

---
> Source: [wardbox/roke](https://github.com/wardbox/roke) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
