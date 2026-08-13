# mcp-go-ftp

> MCP Go FTP Server: Go MCP server for FTP/SFTP/FTPS ops. Enables AI assistants to interact with remote file systems securely.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-go-ftp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

MCP Go FTP Server: Go MCP server for FTP/SFTP/FTPS ops. Enables AI assistants to interact with remote file systems securely.

Features: Multiple connections, file ops (connect, list, upload, download, delete), secure protocols, testing.

Tech: Go 1.26.1+, MCP, golang.org/x/crypto/ssh, github.com/jlaffaye/ftp.

Usage: Build .\compile.bat, config Claude Desktop, use ftp_connect, ftp_upload, ftp_download tools.

Guidelines: Go best practices, error handling, logging, validation, env creds, path sanitization.

---
> Source: [scopweb/mcp-go-ftp](https://github.com/scopweb/mcp-go-ftp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
