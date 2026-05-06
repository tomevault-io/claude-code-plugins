# safe-file-transforms

> File transformation safety patterns for coherent fix

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/safe-file-transforms/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Safe File Transforms

When modifying fix.ts or adding new file transformations:

- Use `safeWrite()` from `./fix-validation.js` instead of `writeFileSync` for all TSX/TS file writes
- `safeWrite` validates TSX syntax after writing and rolls back on failure
- Track modified files in `modifiedFiles` array for post-transform verification
- Never add empty `catch {}` blocks — always log with `chalk.yellow`
- Prefer full component regeneration over regex-based patching

---
> Source: [skovtun/coherent-design-method](https://github.com/skovtun/coherent-design-method) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
