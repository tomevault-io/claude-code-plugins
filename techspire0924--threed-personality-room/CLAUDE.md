# my-threed-rule

> - Code style: TypeScript strict, functional React components, RSC friendly. Prefer server components except where Web APIs/Canvas/R3F need client components.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/my-threed-rule/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Cursor House Rules (Mood Room)
- Code style: TypeScript strict, functional React components, RSC friendly. Prefer server components except where Web APIs/Canvas/R3F need client components.
- Folder structure: app router, feature-based folders, colocate tests.
- Accessibility: keyboard-first, aria-* on interactive controls, reduced motion.
- Performance: lazy-load heavy 3D code, suspense fallbacks, use KTX2/Draco-ready loaders (stub for now).
- State: Zustand for app state, URL search params for share links.
- Testing: Vitest RTL for units, Playwright for E2E (happy path).
- Observability: error boundaries, simple logger, TODO Sentry hook.
- Comments: short top-of-file “Thought Logic” explaining why, not what.

---
> Source: [techspire0924/ThreeD-Personality-Room](https://github.com/techspire0924/ThreeD-Personality-Room) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
