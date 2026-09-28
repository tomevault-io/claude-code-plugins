# molchanica

> Do not add unit tests permanently. You may add them transiently e.g. while adding or updating

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/molchanica/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Unit tests
Do not add unit tests permanently. You may add them transiently e.g. while adding or updating
functionality; clean them up after.


## Code format
Add appropriate line breaks in code; I have noticed LLMs tend to not use
line breaks, which makes it tough for me to read and edit code.


## If on a machine without Cuda/nvidia graphics card
Use the `--no-default-features` flag to compile without needing CUDA.

---
> Source: [David-OConnor/molchanica](https://github.com/David-OConnor/molchanica) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-27 -->
