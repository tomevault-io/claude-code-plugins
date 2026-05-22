# 40-gui-layout

> description: Class-based GUI with deterministic layout and validation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/40-gui-layout/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Class-based GUI with deterministic layout and validation
alwaysApply: false
---

GUI rules
- GUI code must be encapsulated in classes using `Gui()`; no legacy v1 syntax.
- Store control refs in `Map()`; bind with `.OnEvent(..., .Bind(this))`.
- Compute layout deterministically; validate overlaps and boundaries; generate report when debugging.

References
- Modules reference: `Modules/Module_GUI.md`
- Additional examples: `AHK_Notes/Classes/gui-class-best-practices.md`, `AHK_Notes/Concepts/GUI_Controls_and_Patterns.md`

---
> Source: [TrueCrimeDev/ClautoHotkey](https://github.com/TrueCrimeDev/ClautoHotkey) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
