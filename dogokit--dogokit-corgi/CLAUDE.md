# gsap

> When importing the plugin, because we're only using ESM, NOT CommonJS, then do it like this: `"gsap/dist/PluginName"`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gsap/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GSAP library for animation

When importing the plugin, because we're only using ESM, NOT CommonJS, then do it like this: `"gsap/dist/PluginName"`

```tsx
import { gsap } from "gsap";
import ScrollTrigger from "gsap/dist/ScrollTrigger";
import GSAPSplitText from "gsap/dist/SplitText";

gsap.registerPlugin(ScrollTrigger, GSAPSplitText);
```

---
> Source: [dogokit/dogokit-corgi](https://github.com/dogokit/dogokit-corgi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
