# wordai

> - Use four-space indentation and LF line endings.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wordai/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Guidance for Contributors

- Use four-space indentation and LF line endings.
- Run tests with `DOTNET_ROLL_FORWARD=Major dotnet test WordAI.Tests/WordAI.Tests.csproj` before committing.
- The `WordAI.VSTO` project targets .NET Framework 4.8 and requires Visual Studio on Windows; avoid building it on Linux.
- Tag releases as `vX.Y.Z` and push the tag to trigger the GitHub Actions release workflow.
- Keep the signing secrets (`WORDAI_CODE_SIGNING_PFX`, `WORDAI_CODE_SIGNING_PASSWORD`) current in the repository settings.
- Update this file, the README, `CONTRIB.md`, and `RELEASE.md` when build or test instructions change.

---
> Source: [gaspardpetit/WordAI](https://github.com/gaspardpetit/WordAI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-28 -->
