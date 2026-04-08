# gemini-cli-ssh-extension

> This extension provides a robust tool for executing remote commands over SSH using the `paramiko` Python library.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gemini-cli-ssh-extension/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# SSH Extension (v2.1)

This extension provides a robust tool for executing remote commands over SSH using the `paramiko` Python library.

## Authentication

Authentication is handled by the user's local SSH configuration and agent. For best results, ensure your SSH keys are added to your SSH agent. The tool will also respect the `$SSH_KEY_PATH` and `$SSH_PASSWORD` environment variables.

## Available Tools

### `ssh`

-   **Description:** Executes a command on a remote host.
-   **Usage:** The `args` parameter should contain the full command-line string for the SSH connection, in the format `user@hostname "command to run"`.
-   **Example:** `ssh(args='bitnami@123.45.67.89 "ls -la /home/bitnami"')`

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/involvex)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/involvex)
<!-- tomevault:4.0:claude_md:2026-04-07 -->
