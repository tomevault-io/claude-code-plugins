# resume-agent-skills

> For job tailoring runs, use the **`tailor-resume`** skill:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/resume-agent-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Resume repository

For job tailoring runs, use the **`tailor-resume`** skill:

- Read `.cursor/skills/tailor-resume/SKILL.md` (or invoke `/tailor-resume`)
- Treat `resume.md` as the single source of truth for facts
- Write per-job outputs under `jobs/<company-slug>/<role-slug>/`: `fit-report.md`, `tailored-resume.md`, and `change-summary.md`
- In `fit-report.md`, include `**Tier:**` and `**Verdict:**` under **Overall fit**.

Do not invent experience. Unsupported requirements belong in the fit report (**Do not add**), not the tailored resume.

---
> Source: [gopinav/resume-agent-skills](https://github.com/gopinav/resume-agent-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
