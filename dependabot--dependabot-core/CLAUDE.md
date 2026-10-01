# dependabot-core

> NuGet C# development under `nuget/helpers/lib/NuGetUpdater` is an exception to the repository's Docker-only rule.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dependabot-core/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# NuGet Local Development Exception

NuGet C# development under `nuget/helpers/lib/NuGetUpdater` is an exception to the repository's Docker-only rule.
When a compatible .NET SDK is installed, build and test the C# projects directly on the host:

```bash
dotnet build nuget/helpers/lib/NuGetUpdater/NuGetUpdater.slnx
dotnet test nuget/helpers/lib/NuGetUpdater/NuGetUpdater.Core.Test/NuGetUpdater.Core.Test.csproj
```

---
> Source: [dependabot/dependabot-core](https://github.com/dependabot/dependabot-core) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
