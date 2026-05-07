# gemini-cli-extensions

> 1.  **Authorize**: First run spawns a browser for OAuth. Approve `mcp` scope.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gemini-cli-extensions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitLab Gemini CLI Extension

## Quick Start
1.  **Authorize**: First run spawns a browser for OAuth. Approve `mcp` scope.
2.  **Use**: `/gitlab:issue <project> <issue_id>`.

## Commands
Wrappers for GitLab MCP tools. If prompted, re-run with missing args.

- **Issues/MRs/Notes**: `project_id` OR `namespace/project` + `IID`.
    - `/gitlab:issue`, `/gitlab:mr`, `/gitlab:create-issue`, `/gitlab:create-mr`, `/gitlab:create-note`, `/gitlab:workitem-notes`
- **Pipelines**: `project_id` + `pipeline_id`.
    - `/gitlab:pipeline-jobs`, `/gitlab:manage-pipeline`
- **Search**: `scope` + `query`.
    - `/gitlab:search merge_requests "login fix"`, `/gitlab:semantic-search`, `/gitlab:search-labels`

## Troubleshooting
- **Auth Failures**: Re-run command to trigger new device flow. Clear tokens via `~/.gemini/settings.json` if needed.
- **Schemas**: Check params with `/mcp schema gitlab <tool_name>`.
- **Self-Managed**: Update `gemini-extension.json` URL and add `--api-root`.

---
> Source: [GitLab-Ecosystem/Gemini-CLI-Extensions](https://github.com/GitLab-Ecosystem/Gemini-CLI-Extensions) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
