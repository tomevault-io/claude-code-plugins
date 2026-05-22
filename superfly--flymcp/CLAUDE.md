# go

> - Use simple Go project layout

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/go/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Go Development Rules

## Directory Structure
- Use simple Go project layout
  - ./cmd/ for individual subcommands
  - 
- NEVER create a pkg or internal directory

## Code Changes
- Minimize file changes by keeping related functionality together
- Prefer modifying existing files over creating new ones
- Use interfaces to reduce coupling between components

## Library use
- ALWAYS use the go std library when writing new code
- NEVER use a third party package without explicit user request

## Testing
- Tests MUST fail if the code they're testing isn't implemented
- NEVER modify tests to make them pass without implementing the required functionality
- Write tests before implementing features (TDD approach)

---
> Source: [superfly/flymcp](https://github.com/superfly/flymcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
