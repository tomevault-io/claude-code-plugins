# qr-dart

> - see pubspec.yaml for SDK constraints

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/qr-dart/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Rules for AI Agents

## Tech Stack
- **Language**: Dart
  - see pubspec.yaml for SDK constraints
- **Web**: `package:web` (do NOT use `dart:html`)
- **Testing**: `package:test`

## Code Style

Reference `analysis_options.yaml` for lint rules.

## Testing

Reference `CONTRIBUTING.md` for testing information.

## Web Development

Reference `CONTRIBUTING.md` for web development information.

## General
- Keep changes minimal and focused.
- Follow existing patterns in the codebase.
- Always check analyzer for lints and fix them.

### Troubleshooting
If `dart run build_runner serve` fails with "address in use", you can search for the process using the port (e.g. 8080) using `witr`.

```bash
witr -o 8080 --json
```

If the output indicates that `build_runner` is already serving the current directory, you can reuse that instance.
Otherwise, you should prompt the user to stop the conflicting process.

---
> Source: [kevmoo/qr.dart](https://github.com/kevmoo/qr.dart) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
