# ffgl-rs

> This respository holds a rust ffgl plugin framework for resolume.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ffgl-rs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Intro

This respository holds a rust ffgl plugin framework for resolume.
It also holds a plugin that takes an ISF shader and compiles it as a plugin.

Assume that .fs files are ISF shaders and .rs files are rust files.

When making animating shaders, try to use a progress variable that goes from 0 to 1. This will allow the shader to be animated in resolume by manipulating the progress variable.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/edeetee) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
