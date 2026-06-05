# clarify-before-coding

> Ask clarifying questions before generating code when requirements are unclear

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/clarify-before-coding/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Clarify Before Coding

- Do not write or modify code until task requirements are clear.
- Ask the user specific questions when scope, behavior, or acceptance criteria are ambiguous.
- For **bug reports**, investigate root cause first; do not "fix" by swallowing errors or silent fallbacks (see `AGENTS.md` — Error handling).

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
