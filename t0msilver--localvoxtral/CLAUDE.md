# localvoxtral

> STOP: before changing anything here (or in `Sources/ClaudeContext*` /

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/localvoxtral/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Claude Code context path — agent notes

STOP: before changing anything here (or in `Sources/ClaudeContext*` /
`integrations/claude-code/`), read `../../../docs/agent/invariants.md` in
full. Every join arm, trust boundary, and fail-closed rule in this subtree is
deliberate, most encode measured failures, and several are security
boundaries (transport-derived trust, `LocalWorkspacePath`'s no-public-init
rule, abstain-on-ambiguity). These paths are also LLM-lane-relevant
(`scripts/ci/llm-lane-filter.sh`).

---
> Source: [T0mSIlver/localvoxtral](https://github.com/T0mSIlver/localvoxtral) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
