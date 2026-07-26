# ffilesystem

> when building the project code, use CMake presets

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ffilesystem/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


* build and test project code: `cmake --workflow default`
* only build the project code-this disables tests, so don't use this when working on tests: `cmake --workflow build`
* if working with project tests, use `cmake --build build` to build the project code and tests, then use `ctest --test-dir build` to run the tests using `-R` to specify which tests to run, e.g. `ctest --test-dir build -R copyfile` to run only the `copyfile` test

---
> Source: [scivision/ffilesystem](https://github.com/scivision/ffilesystem) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
