# mark-circuits

> MARK Circom circuit soundness, completeness, and validation rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mark-circuits/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# MARK Circuits

Follow root `AGENTS.md` for validation routing. Circuits are security-critical because proof verification must imply knowledge of valid witness data.

## Security Rules

- No unconstrained `<--` assignments.
- No unused signals.
- No `block.timestamp` or chain-time assumptions inside circuits.
- Preserve public-signal ordering expected by contracts.
- Nullifier and commitment logic must prevent double-spends and preserve privacy.

## Validation

- JS/test harness only: `pnpm circuits:test`
- `.circom` changes: `pnpm circuits:test` and `mise run circomspect`
- Soundness: `pnpm --filter @mark/circuits run test:soundness`
- Completeness: `pnpm --filter @mark/circuits run test:completeness`

If Circom fails with `/usr/local/bin/circom: line 1: Not: command not found` or `Not Found/usr/local/bin/circom`, treat it as a local toolchain issue first, not proof of a circuit regression.

---
> Source: [trade/mark](https://github.com/trade/mark) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-06 -->
