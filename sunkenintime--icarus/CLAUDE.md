# code-gen-rules

> When modifying Dart code that uses build_runner code generation (.g.dart, .freezed.dart). Edit source files only—never edit generated files directly. Run build_runner after changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/code-gen-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Use the appropriate channels and make your changes in the source files that generate the code. If you need to modify anything that appears in a generated file (such as `.g.dart`), update the original source file instead — never edit generated files directly.  

After making changes, run:

```bash
dart run build_runner build --delete-conflicting-outputs
```

---
> Source: [SunkenInTime/icarus](https://github.com/SunkenInTime/icarus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-02 -->
