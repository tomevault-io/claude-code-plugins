# cinematic-webscroll-frontend-skill

> Use the `cinematic-web-experiences` workflow when a request involves cinematic websites, scroll storytelling, GSAP ScrollTrigger, Three.js scenes, custom shaders, loading screens, or premium motion-heavy landing pages.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cinematic-webscroll-frontend-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidance

Use the `cinematic-web-experiences` workflow when a request involves cinematic websites, scroll storytelling, GSAP ScrollTrigger, Three.js scenes, custom shaders, loading screens, or premium motion-heavy landing pages.

Preferred references:

- `shared/cinematic-web-experiences/guide.md`
- `.codex/skills/cinematic-web-experiences/SKILL.md`
- `.cursor/skills/cinematic-web-experiences/SKILL.md`
- `.claude/cinematic-web-experiences.md`

Default expectations:

- use exact visual tokens
- pick the animation stack before writing motion
- define sections before animation specs
- pin `three@0.136.0` and `@types/three@0.136.0` for Three.js
- finish with explicit responsive rules and `overflow-x: hidden`
- if source media does not exist yet, optionally use the `fal-ai-community/skills` repo to generate images or video assets first
- if the frontend is text-heavy or editorial, optionally use `pretext` for accurate multiline text measurement and layout

---
> Source: [amrrs/cinematic-webscroll-frontend-skill](https://github.com/amrrs/cinematic-webscroll-frontend-skill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
