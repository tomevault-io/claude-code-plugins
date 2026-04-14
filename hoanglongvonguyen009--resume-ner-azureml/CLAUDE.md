# resume-ner-azureml

> Keep notebooks as orchestration; move reusable logic into src/.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/resume-ner-azureml/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Notebook Rules

- **Keep notebooks thin**: Notebooks should be orchestration, visualization, and calling functions.
- **Extract reusable logic**: If logic grows (selection, preprocessing, metrics, config parsing), extract it into `src/` as typed functions and import them.
- **Type-check the real logic**: New reusable logic must go into `src/` with type hints so Mypy can check it.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/hoanglongvonguyen009) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
