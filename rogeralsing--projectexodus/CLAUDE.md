# projectexodus

> To build and test this repository locally, ensure the .NET SDK 9.0 or newer is installed.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/projectexodus/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

To build and test this repository locally, ensure the .NET SDK 9.0 or newer is installed.

## Installing with apt (Ubuntu)
```bash
wget https://packages.microsoft.com/config/ubuntu/24.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo apt-get update
sudo apt-get install -y dotnet-sdk-9.0
```

## Installing with script
If the SDK is unavailable from packages, use the official install script:
```bash
wget https://dot.net/v1/dotnet-install.sh -O dotnet-install.sh
chmod +x dotnet-install.sh
./dotnet-install.sh --channel 9.0
export PATH="$PATH:$HOME/.dotnet"
```
After installation, run tests with `dotnet test`.

---
> Source: [rogeralsing/ProjectExodus](https://github.com/rogeralsing/ProjectExodus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
