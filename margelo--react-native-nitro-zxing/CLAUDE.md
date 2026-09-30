# react-native-nitro-zxing

> - `packages/react-native-nitro-zxing` is a Nitro Module implemented in C++ (`cpp/`). zxing-cpp lives in the `cpp/zxing-core` git submodule - never edit or format files inside it; run `git submodule update --init` after cloning.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/react-native-nitro-zxing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository agent guidance

- `packages/react-native-nitro-zxing` is a Nitro Module implemented in C++ (`cpp/`). zxing-cpp lives in the `cpp/zxing-core` git submodule - never edit or format files inside it; run `git submodule update --init` after cloning.
- After changing `src/specs/*.nitro.ts`, run `bun specs` and commit `nitrogen/generated`.
- `apps/example` is the example and benchmark app (`ScannerScreen`, `BenchmarkScreen`). Benchmark numbers in the README come from a release build on a physical device.
- Keep PRs small: single atomically testable/mergeable/revertable changes.

---
> Source: [margelo/react-native-nitro-zxing](https://github.com/margelo/react-native-nitro-zxing) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
