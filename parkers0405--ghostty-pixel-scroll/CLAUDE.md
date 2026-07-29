# ghostty-pixel-scroll

> The inspector is a feature of Ghostty that works similar to a

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ghostty-pixel-scroll/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Inspector Subsystem

The inspector is a feature of Ghostty that works similar to a
browser's developer tools. It allows the user to inspect and modify the
terminal state.

- See the full C API by finding `dcimgui.h` in the `.zig-cache` folder
  in the root: `find . -type f -name dcimgui.h`. Use the newest version.
- See full examples of how to use every widget by loading this file:
  <https://raw.githubusercontent.com/ocornut/imgui/refs/heads/master/imgui_demo.cpp>
- On macOS, run builds with `-Demit-macos-app=false` to verify API usage.
- There are no unit tests in this package.

---
> Source: [parkers0405/ghostty-pixel-scroll](https://github.com/parkers0405/ghostty-pixel-scroll) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
