# ninjaone

> Use for PowerShell files in the NinjaOne repo: preserve formatting, help, metadata, and cross-platform compatibility patterns.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ninjaone/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


PowerShell file instructions
============================

* Match the existing repository style and indentation.
* Add or preserve comment-based help where required.
* For public cmdlets, keep parameter naming and `MetadataAttribute` usage consistent with nearby commands.
* Prefer fixes that work on both Windows PowerShell and PowerShell 7 on Linux.
* Avoid brittle path assertions or OS-specific assumptions in tests.
* When adjusting tests, validate real behavior rather than mock-only artifacts.

---
> Source: [homotechsual/NinjaOne](https://github.com/homotechsual/NinjaOne) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
