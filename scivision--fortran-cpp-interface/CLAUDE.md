# fortran-cpp-interface

> when building the project code, use CMake presets

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fortran-cpp-interface/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


* build and test project code: `cmake --workflow default`
* only build the project code: `cmake --workflow build`

* Notice that the test/*/CMakeLists.txt files have directory property LABELS set that can be used to run a subset of tests with `ctest -L <label>` (e.g. `ctest -L allocate` to run only the tests in test/allocate)

---
> Source: [scivision/fortran-cpp-interface](https://github.com/scivision/fortran-cpp-interface) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
