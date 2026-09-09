# polox-ui

> Preserve the Polox.ai dark creative-workspace UI across frontend changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/polox-ui/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


For every frontend or visual change, use the `polox-ui` project skill at `../skills/polox-ui/SKILL.md` and read its design-system reference before editing.

- Treat `app/assets/css/tailwind.css` as the token source of truth.
- Keep the dark canvas, tonal panels, hairline borders, controlled 8/12/16px radii, and restrained acid-lime accent.
- Reuse existing Nuxt and shadcn-vue primitives; preserve responsive and accessible states.
- Visually verify changed routes after implementation.

---
> Source: [saihhold-zhao/polox_ai](https://github.com/saihhold-zhao/polox_ai) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
