# lens-studio-scene-edits

> Lens Studio scene edits must go through the user-lens-studio MCP, not raw Scene.scene writes

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/lens-studio-scene-edits/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Lens Studio scene edits

Do **not** write or edit `lens-studio/Assets/Scene.scene` (or other `.scene` files) directly.

Use the **`user-lens-studio` MCP tools** for all scene-object investigation and manipulation (create/move/rename objects, wire components, inspect hierarchy).

Raw scene-file edits are not allowed. If the MCP cannot express a change, stop and ask the user rather than patching `Scene.scene` by hand.

---
> Source: [V4C38/spectacles-dimensional-os](https://github.com/V4C38/spectacles-dimensional-os) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
