# design-system

> Keep docs/DESIGN_SYSTEM.md updated when design tokens or shared UI change

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/design-system/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Design system documentation

Canonical reference: [`docs/DESIGN_SYSTEM.md`](../../docs/DESIGN_SYSTEM.md)

When adding or changing design-system items, update that file in the same change:

- **Tokens** (colors, spacing, radius, shadows, typography) in `src/design/`
- **Motion** presets in `src/ui/motion/`
- **Shared UI components** in `src/components/ui/` or `src/ui/`
- **Visual patterns** (glass, sheets, chrome, cards)

Add a row to the **Changelog** section with the date and a one-line summary.

Use `useTheme()` for scaled tokens in components. Follow the [Apple HIG rule](./apple-hig.mdc) for spacing, touch targets, and sheets.

---
> Source: [cameronconspm/Listio](https://github.com/cameronconspm/Listio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
