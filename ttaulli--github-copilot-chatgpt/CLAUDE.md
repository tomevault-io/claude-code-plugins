# github-copilot-chatgpt

> - When asked to fix code, first explain the problems found.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/github-copilot-chatgpt/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Operator Interaction
- When asked to fix code, first explain the problems found.
- When asked to generate tests, first explain what tests will be created.
- When making multiple changes, provide a step-by-step overview first.

## Security
- Check the code for vulnerabilities after generating.
- Avoid hardcoding sensitive information like credentials or API keys.
- Use secure coding practices and validate all inputs.

## Environment Variables
- If a .env file exists, use it for local environment variables.
- Document any new environment variables in README.md.
- Provide example values in .env.example.

## Version Control
- Keep commits atomic and focused on single changes.
- Follow conventional commit message format.
- Update .gitignore for new build artifacts or dependencies.

## Change Logging
- Each time you generate code, note the changes in changelog.md in the root of the repo
- Follow semantic versioning guidelines
- Include date and description of changes

## For Python Projects Only
- Follow PEP 8 style guidelines
- Include type hints (PEP 484)

---
> Source: [ttaulli/GitHub-Copilot-ChatGPT](https://github.com/ttaulli/GitHub-Copilot-ChatGPT) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
