# slimgui

> - Keep recipe examples idiomatic for Dear ImGui and Slimgui. The preferred patterns should match how similar problems are solved in `src/c/imgui/imgui_demo.cpp`, even when the recipe is simplified for documentation.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/slimgui/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Recipe Example Guidelines

- Keep recipe examples idiomatic for Dear ImGui and Slimgui. The preferred patterns should match how similar problems are solved in `src/c/imgui/imgui_demo.cpp`, even when the recipe is simplified for documentation.
- A recipe example should primarily be a single standalone example function. Use a separate state dataclass only when state is actually needed for the interaction being demonstrated.
- The function docstring is the primary explanation of the recipe. Write it as the text that should appear in the generated markdown page, with enough detail for both human readers and LLMs to understand what the example is doing and why.
- Keep the code focused on one pattern. Avoid defensive scaffolding or incidental abstractions unless they are part of the recipe being taught.

---
> Source: [nurpax/slimgui](https://github.com/nurpax/slimgui) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
