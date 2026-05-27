# flake

> - **Build**: `nix build .#<host>` or `nixos-rebuild build --flake .#<host>`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/flake/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# NixOS Flake Agent Guide

## Build & Deploy
- **Build**: `nix build .#<host>` or `nixos-rebuild build --flake .#<host>`
- **Switch**: `nixos-rebuild switch --flake .#<host>` (NixOS) / `darwin-rebuild switch --flake .#<host>` (Darwin)
- **Home**: `home-manager switch --flake .#<home>`

## Lint & Format
- **Nix**: `nix fmt` (uses alejandra)
- **Lua**: `stylua .` (2-space indent, 160 column width, AutoPreferSingle quotes)

## Code Style
- **Nix**: 2-space indent, use `let...in` for locals, prefer `inherit` for imports
- **Imports**: Simple list format: `imports = [ ./file.nix ]`
- **Naming**: camelCase for functions/variables, PascalCase for modules/components
- **Files**: lowercase for system configs, descriptive names for modules
- **Structure**: Group related configs in directories with `default.nix` exports

## Testing
- **Nix**: `nix flake check` (validates flake structure)
- **Config**: `nixos-rebuild test --flake .#<host>` (test without switching)

## Subprojects
- See `nvim/` for Neovim Lua configuration

---
> Source: [GMkonan/flake](https://github.com/GMkonan/flake) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-27 -->
