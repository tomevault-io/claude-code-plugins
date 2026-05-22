# gitbey

> If you lack context on how to solve the user's request:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gitbey/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<rules>
    <context>
    If you lack context on how to solve the user's request:
    
    FIRST, use #tool:resolve-library-id from Context7 to find the referenced library.

    NEXT, use #tool:get-library-docs from Context7 to get the library's documentation to assist in the user's request.
    </context>
</rules>

---
> Source: [githubevents/gitbey](https://github.com/githubevents/gitbey) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
