# fastsurfer

> - Follow [CONVENTIONS.md](CONVENTIONS.md) when writing or changing documentation: the Markdown and reST files in

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fastsurfer/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Instructions for agents working on the documentation

- Follow [CONVENTIONS.md](CONVENTIONS.md) when writing or changing documentation: the Markdown and reST files in
  `doc/` and the files they include with `.. include::` (for example `README.md` and `tools/Docker/README.md`).
- `AGENTS.md` and `CONVENTIONS.md` are not part of the built documentation, `exclude_patterns` in `doc/conf.py` lists
  them.
- Markdown is parsed by the `fix_links` extension (`doc/sphinx_ext/fix_links`), which extends MyST: among others, it
  substitutes `{{ NAME }}` in code and renders banners on top of code blocks, see CONVENTIONS.md.
- Check changes by building the documentation from the repository root, warnings are errors:

  ```bash
  uv run --extra doc sphinx-build -WT --keep-going -j auto doc doc-build
  ```

---
> Source: [Deep-MI/FastSurfer](https://github.com/Deep-MI/FastSurfer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
