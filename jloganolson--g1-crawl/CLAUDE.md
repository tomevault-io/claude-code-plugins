# conda

> Best practices

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/conda/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- Whenever running python in this project, use the `g1-crawl` conda env (e.g. `conda activate g1-crawl && python test.py`)
- Do not code quiet failure/backup cases (e.g. try/catch or `if x is None`) - we'd rather fail loudly

---
> Source: [jloganolson/g1_crawl](https://github.com/jloganolson/g1_crawl) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
