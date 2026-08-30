# fpga-compile

> FPGA compiles must use GitHub Actions only; never local Rosetta Quartus

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fpga-compile/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# FPGA compile — GitHub Actions only

- **NEVER** run Quartus locally on this Mac.
- **NEVER** use `quartus-mister-rosetta`, local `docker run … quartus_sh`,
  or any amd64 Quartus under Rosetta. It does not work for us.
- **ALWAYS** compile via GitHub Actions `.github/workflows/build-core.yml`.
  Push the FPGA source, then `gh workflow run build-core.yml --ref <branch>`
  (or rely on the `fpga/**` push trigger). Download the `DVD.rbf` artifact.

---
> Source: [joedaniels198512-gif/dvd-core](https://github.com/joedaniels198512-gif/dvd-core) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-29 -->
