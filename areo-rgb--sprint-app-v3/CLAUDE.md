# sprint-app-v3

> Always use jCodemunch-MCP tools — never fall back to Read, Grep, Glob, or Bash for code exploration.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sprint-app-v3/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Code Exploration Policy
Always use jCodemunch-MCP tools — never fall back to Read, Grep, Glob, or Bash for code exploration.
- Before reading a file: use get_file_outline or get_file_content
- Before searching: use search_symbols or search_text
- Before exploring structure: use get_file_tree or get_repo_outline
- Call resolve_repo with the current directory first; if not indexed, call index_folder.


IMPORTANT: After any file edit, immediately refresh jCodemunch context for changed files (use `register_edit` with `reindex=true`, or `index_file`) before further symbol reads/patching to avoid stale tool results.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Areo-RGB) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
