# alternative-heycyan-app-and-sdk

> Software Development Kit (SDK) for HeyCyan Smart Glasses. Contains core libraries and sample applications for integrating features like camera access, sensor data, and display control.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/alternative-heycyan-app-and-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md - HeyCyanSmartGlassesSDK

## Purpose
Software Development Kit (SDK) for HeyCyan Smart Glasses. Contains core libraries and sample applications for integrating features like camera access, sensor data, and display control.

## Project Structure
- `android/`: Android-specific SDK code and demo apps.
- `ios/`: iOS-specific SDK code and sample projects.
- `examples/`: Cross-platform or specific usage examples.
- `firmware_dump/`: Hardware firmware reference or dumps.
- `QCSDK.framework/`: Pre-compiled framework for iOS development.

## Android Data Transfer Notes

- Media transfer (BLE + Wi-Fi Direct HTTP) reverse-engineering notes live in `android/AGENTS.md`.

## Development Environment
- **Conda Environment:** `LocalGPT_llama2`
- **STRICT RULE:** Never use `pip install` or download libraries into the `base` conda environment.

## Execution Rules
- Review `WIFI_TRANSFER_ARCHITECTURE.md` before working on data transmission features.
- Ensure any demo app changes are tested against the physical device if available.

---
> Source: [FerSaiyan/Alternative-HeyCyan-App-and-SDK](https://github.com/FerSaiyan/Alternative-HeyCyan-App-and-SDK) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
