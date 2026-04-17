# iso-auc-curves-deploy

> Building interactive data apps using Python.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/iso-auc-curves-deploy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Context
Building interactive data apps using Python.

# Tech Stack
- **Marimo:** For the notebook interface (files are .py).
- **Polars:** For data handling.
- **Plotly:** For plotting (preferred over Matplotlib for Marimo).

# Coding Standards
- **Reactivity:** Ensure UI elements (sliders) directly filter dataframes.
- **Format:** Output code as a valid marimo `.py` file (using `@app.cell` decorators).
- **Style:** Use `mo.vstack` or `mo.hstack` to organize the layout cleanly.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Victor-Calzada) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-11 -->
