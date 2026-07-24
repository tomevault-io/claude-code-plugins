# core

> - The codebase is built using `bazel`. Also use `bazel` to run tests.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/core/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project: CloudRobotics Core

## General Instructions

- The codebase is built using `bazel`. Also use `bazel` to run tests.
- After editing .src/go.mod or changing `deps` in BUILD.bazel files, run `bazel run //:gazelle`
- ./src/go/pkg/apis contains generated code. Do not edit.
- ./scripts contains maintenance scripts. Do not run them.
- Consider documentation from ./docs for extra context.
- For more information about this project, read @README.md in the root of this
  repository as well as @./src/README.md.

---
> Source: [googlecloudrobotics/core](https://github.com/googlecloudrobotics/core) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
