# mediaforge

> - Separate View, ViewModel, and Model layers

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mediaforge/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# WPF/C# Development Rules
# Activation: Glob pattern *.cs, *.xaml

## MVVM Pattern
- Separate View, ViewModel, and Model layers
- Use INotifyPropertyChanged for bindings
- Implement ICommand for button actions
- Use dependency injection for services

## Event Handling
- Unsubscribe events in Dispose/Unloaded
- Use weak event patterns for long-lived objects
- Implement proper command binding
- Add visual feedback for all interactions

## Async Operations
- Use async/await for I/O operations
- Update UI on dispatcher thread
- Show loading indicators during operations
- Handle cancellation properly

## API Communication
- Use HttpClient with proper disposal
- Implement retry policies
- Handle network failures gracefully
- Cache responses where appropriate

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Ghenghis) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
