# modeling-app

> Files under `public/kcl-samples` are user-facing, current KCL examples. Write

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/modeling-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Modeling-app agent notes

## Current KCL samples

Files under `public/kcl-samples` are user-facing, current KCL examples. Write
constraint-based sketch blocks with `sketch(on = ...) { ... }`, build closed
profiles with `region(...)`, and use `faceOf(...)` for sketching on solid faces.

Do not use deprecated profile-pipe sketch APIs in current samples, including
`startSketchOn`, `startProfile`, `xLine`, `yLine`, `angledLine`,
`tangentialArc`, or `close()`. Do not pass a sketch or surface as a positional
argument to `circle`, `rectangle`, or `polygon`; define those segments inside
a sketch block. Compatibility examples belong under `public/kcl-samples-legacy`.

Format and lint every changed KCL file with Zoo CLI. Execute and visually
compare affected samples before claiming that their geometry is preserved.

---
> Source: [KittyCAD/modeling-app](https://github.com/KittyCAD/modeling-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-16 -->
