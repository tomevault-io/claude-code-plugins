# smavg

> Build the core first. Do not spend effort on skills, MCP, REST, dashboards,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/smavg/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Smavg Agent Instructions

## Project Rule

Build the core first. Do not spend effort on skills, MCP, REST, dashboards,
installers, or FUSE wrappers until the local storage round-trip is measurable
and byte-perfect.

## Success Criteria

- Measure a real source folder.
- Store files through Smavg.
- Report actual store size from disk.
- Restore every file byte-perfect.
- Do not simulate benchmark numbers.

## Phase 1 Bias

Prefer simple Python code that proves correctness and produces honest numbers.
Keep the public interface stable enough that MiniLM, ChromaDB, bsdiff, FUSE, and
Rust can replace internals later without rewriting the proof workflow.

---
> Source: [aegiswizard/smavg](https://github.com/aegiswizard/smavg) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-24 -->
