# r9

> r9 is a cross-platform Plan9-inspired OS written in Rust.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/r9/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

r9 is a cross-platform Plan9-inspired OS written in Rust.

The architectures supported are: aarch64, x86-64 and riscv64.

The project must be free of errors and warnings at all times, including those from check and clippy, and for all supported architectures.  All tests must pass.

## Commands
- Build:
  - aarch64: `cargo xtask dist --arch aarch64`
  - riscv64: `cargo xtask dist --arch riscv64`
  - x86-64: `cargo xtask dist --arch x86-64`
- Check:
  - `cargo xtask dist`
- Clippy:
  - aarch64: `cargo xtask clippy --arch aarch64`
  - riscv64: `cargo xtask clippy --arch riscv64`
  - x86-64: `cargo xtask clippy --arch x86-64`
- Test:
  - `cargo xtask test`

---
> Source: [r9os/r9](https://github.com/r9os/r9) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
