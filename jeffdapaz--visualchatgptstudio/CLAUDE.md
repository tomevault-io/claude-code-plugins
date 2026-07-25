# visualchatgptstudio

> - When making changes, do not modify functionalities that already work/tested; implement only the specific requested change, with the smallest possible impact.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/visualchatgptstudio/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## General Guidelines
- When making changes, do not modify functionalities that already work/tested; implement only the specific requested change, with the smallest possible impact.
- Always write code in English.
- Make implementations step-by-step, and be detailed in your response, never assuming the user will understand everything.
- If you have doubts, ask the user for clarification before implementing.
- When creating new classes, add the following standard regions in the order below, and always close them with "endregion": 
	- Constants 
	- Properties 
	- Constructors 
	- Public Methods 
	- Private Methods
- When creating methods, respect the regions already present in the file when they exist. For example, public methods should be placed in the public methods region, private methods in the private methods region, etc.
- When creating methods, properties, etc., always add comments using the C# "<summary>" pattern.

---
> Source: [jeffdapaz/VisualChatGPTStudio](https://github.com/jeffdapaz/VisualChatGPTStudio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
