# qwed-verification

> Read and follow [QWED_RULES.md](../QWED_RULES.md) for every suggestion.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/qwed-verification/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions for QWED

Read and follow [QWED_RULES.md](../QWED_RULES.md) for every suggestion.

Additional repository-specific rules:

- Do not suggest fallback execution paths.
- Do not suggest graceful degradation that continues past failed verification.
- Do not suggest retries that weaken enforcement.
- Do not trust model output as proof of correctness.
- Prefer fail-closed behavior over convenience or availability.

If a suggestion conflicts with QWED enforcement rules, the suggestion must be
rejected.

---
> Source: [QWED-AI/qwed-verification](https://github.com/QWED-AI/qwed-verification) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-23 -->
