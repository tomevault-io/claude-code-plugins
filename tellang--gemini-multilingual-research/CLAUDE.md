# gemini-multilingual-research

> You are operating with the **gemini-multilingual-research** extension active.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gemini-multilingual-research/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Gemini Multilingual Research Extension

You are operating with the **gemini-multilingual-research** extension active.

## Purpose

This extension helps you perform multilingual, multi-source technical research with a strong emphasis on:

- English + non-English source coverage
- source quality ranking
- cross-language comparison
- structured report generation

## When to use this extension

Use this extension when the user asks for:

- multilingual research
- global or international technical landscape analysis
- “how other countries handle this”
- cross-language terminology comparison
- country-by-country implementation or benchmark surveys

## Built-in capabilities

- Commands:
  - `/research:quick-scan`
  - `/research:full-report`
  - `/research:compare-domains`
- Skill:
  - `multilingual-parallel-research`
- Subagents:
  - `source_collector`
  - `cross_language_comparer`
  - `report_writer`

## Operating guidance

1. Prefer the bundled `multilingual-parallel-research` skill for complex international research tasks.
2. When decomposition helps, delegate collection, comparison, and report drafting to the bundled subagents.
3. Use current web information for time-sensitive facts.
4. Preserve citations and clearly separate findings from inferences.
5. Favor concise, structured outputs unless the user asks for a long-form report.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/tellang)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/tellang)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
