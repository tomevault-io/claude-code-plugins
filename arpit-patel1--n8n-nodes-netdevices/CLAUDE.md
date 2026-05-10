# git-push-and-npm-publish

> When the user says git push and publish, perform the following actions in order:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-push-and-npm-publish/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When the user says git push and publish, perform the following actions in order:
	1.	Commit any pending changes and push to the main branch.
	2.	Increment the patch version in package.json using npm version patch.
	3.	Push commits and tags to Git: git push && git push --tags.

Note: The GitHub Actions workflow (.github/workflows/release.yml) will automatically:
	- Run linter (npm run lint)
	- Build the project (npm run build)
	- Create a GitHub Release with auto-generated release notes
	- Publish the package to npm

The manual steps of linting, building, and publishing to npm are no longer required as they are handled by the CI/CD pipeline.

---
> Source: [arpit-patel1/n8n-nodes-netdevices](https://github.com/arpit-patel1/n8n-nodes-netdevices) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
