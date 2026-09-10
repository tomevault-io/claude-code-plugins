# godot-flight-navigation-3d

> - All components are 0.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/godot-flight-navigation-3d/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Test cases guidelines
## Encode/Decode
- All components are 0.
- One component is max value. The others are 0.
- An usual case, where all components are different from 0 and at most 4 bits long per component.

## Add/sub morton codes
- An usual case, where all components are different from 0 and at most 4 bits long per component.
### Add
- One overflow case, where all components overflow.
### Sub
- One underflow case, where all components underflow.

## Add/sub x/y/z
- An usual case, where all components are different from 0 and at most 4 bits long per component.
### Add
- One overflow case.
- One underflow case, when input amount is negative
### Sub
- One underflow case.
- One overflow case, when input amount is negative

## Inc/dec x/y/z
- An usual case, where all components are different from 0 and at most 4 bits long per component.
### Inc
- One overflow case.
### Dec
- One underflow case.

---
> Source: [RevolNoom/godot_flight_navigation_3d](https://github.com/RevolNoom/godot_flight_navigation_3d) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
