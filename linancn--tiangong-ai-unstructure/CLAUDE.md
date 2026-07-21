# tiangong-ai-unstructure

> - Read the target script before changing journal processing behavior.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tiangong-ai-unstructure/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Journals Agent Notes

- Read the target script before changing journal processing behavior.
- Legacy pickle scripts: `src/journals/file_to_pickle.py` and
  `src/journals/file_to_pickle1.py` through `file_to_pickle4.py`.
- Two-stage queue scripts: `src/journals/two_stage_enqueue.py` and
  `src/journals/two_stage_enqueue_urgent.py`.
- Legacy pickle scripts use `TOKEN` plus PostgreSQL env vars. Two-stage scripts
  use `FASTAPI_BEARER_TOKEN` plus optional `TWO_STAGE_*` env vars.
- Outputs include `docs/processed_docs/journal_new_pickle`,
  `journal_pickle_queue`, and script-specific log/error files.

---
> Source: [linancn/TianGong-AI-Unstructure](https://github.com/linancn/TianGong-AI-Unstructure) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
