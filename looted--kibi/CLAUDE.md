# kibi-traceability

> Requirement traceability and symbol linking through Kibi

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kibi-traceability/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Before changing production code, discover linked requirements with `kb_search` and `kb_query(sourceFile=...)`.

After meaningful source edits, run `kb_check({sourceFiles:[...], includeImpactDiagnostics:true, includeWorkingTreeDiff:true})` while the edit context is fresh. Review symbol granularity and whether linked requirements, scenarios, and tests still cover the changed behavior or UI copy.

Preserve the canonical chain `REQ-* -> SCEN-* -> TEST-*` when modeling behavior.

Prefer symbol manifest + `executable_for` for test/e2e code. Inline `// implements REQ-xxx` remains acceptable for quick code-only changes.

Route durable domain facts to strict `fact` entities. Use `fact_kind: observation` or `meta` for bugs and workarounds, not `flag`.

---
> Source: [Looted/kibi](https://github.com/Looted/kibi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-07 -->
