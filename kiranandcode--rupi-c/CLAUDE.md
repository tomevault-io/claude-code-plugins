# rupi-c

> NO UNVERIFIED ARTIFACTS.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rupi-c/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

NO UNVERIFIED ARTIFACTS.

Never add, suggest, or preserve an unverified assembly lane.

Do not emit SQLite assembly unless the Rocq proof closes with `Qed`.

`Abort` means pending. It must not feed benchmarks, linking, or baselines.

The witness `R` is an `Asm.program` produced by CompCert:

```coq
Compiler.transf_c_program source = OK R
```

All SQLite contexts must reduce to concrete `Csyntax.program` sources.

---
> Source: [kiranandcode/rupi-c](https://github.com/kiranandcode/rupi-c) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
