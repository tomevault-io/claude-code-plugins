# design-system

> BrewUI design system — use Theme tokens in app SwiftUI code.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/design-system/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Brew design system (app UI)

- **Colours / styles:** Use `Color.brew…` and `ShapeStyle` helpers from `Brew/Theme/BrewColors.swift` with asset catalog sets — do not use raw hex, `Color(red:…)`, or ad-hoc `Color("…")` in views. If a semantic colour is missing, add a named token in `BrewColors.swift` and a matching colourset.
- **Layout:** Use `BrewLayout`, `BrewSpacing`, and `BrewRadius` from `Brew/Theme/BrewSpacing.swift` instead of magic numbers.
- **Typography:** Use `Font.brew…` from `Brew/Theme/BrewFonts.swift` and semantic text colours from `BrewColors`.
- **Shadows:** Prefer `brewShadowSmall` / `brewShadowMedium` / `brewShadowLarge` when elevation is needed.
- **New patterns:** Extend `Brew/Theme/` rather than scattering one-off values in feature views.

See also `CONVENTIONS.md` — **Design system**.

---
> Source: [Homebrew/BrewUI](https://github.com/Homebrew/BrewUI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
