# ghostty-pixel-scroll

> A file for [guiding coding agents](https://agents.md/).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ghostty-pixel-scroll/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:



A file for [guiding coding agents](https://agents.md/).

## Commands

- **Build:** `zig build`
- **Test (Zig):** `zig build test`
- **Test filter (Zig)**: `zig build test -Dtest-filter=<test name>`
- **Formatting (Zig)**: `zig fmt .`
- **Formatting (other)**: `prettier -w .`

## Directory Structure

- Shared Zig core: `src/`     
- C API: `include`
- macOS app: `macos/`
- GTK (Linux and FreeBSD) app: `src/apprt/gtk`


## libghostty-vt

- Build: `zig build lib-vt`
- Build Wasm Module: `zig build lib-vt -Dtarget=wasm32-freestanding`
- Test: `zig build test-lib-vt`
- Test filter: `zig build test-lib-vt -Dtest-filter=<test name>`
- When working on libghostty-vt, do not build the full app.
- For C only changes, don't run the Zig tests. Build all the examples.

## macOS App

- Do not use `xcodebuild`
- Use `zig build` to build the macOS app and any shared Zig code
- Use `zig build run` to build and run the macOS app
- Run Xcode tests using `zig build test`

---
> Source: [parkers0405/ghostty-pixel-scroll](https://github.com/parkers0405/ghostty-pixel-scroll) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
