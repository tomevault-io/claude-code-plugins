# vl-nurbsy

> - First general instruction

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vl-nurbsy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## General Guidelines
- First general instruction
- Second general instruction

## Code Style
- Use specific formatting rules
- Follow naming conventions

## Project-Specific Rules
- In the VL.Nurbsy project, use immutable collections with reference equality for change detection.
- The `NurbsSurfaceNode` base class handles `Build()` via the `Invalidate()/Update()` pattern called each frame.
- Conversion from `T` to `ControlPoint<T>` is intentional to bridge the user-facing simple API with internal weighted control points.

---
> Source: [antokhio/VL.Nurbsy](https://github.com/antokhio/VL.Nurbsy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
