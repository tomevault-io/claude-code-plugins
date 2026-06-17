# qr-code-system

> QR Code Event Management System

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/qr-code-system/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

QR Code Event Management System

This workspace contains a complete QR code event management system built with Node.js and Express.

## Features
- Upload Excel files with attendee data
- Generate unique QR codes for each attendee
- Real-time QR code scanning and validation
- One-time use security (QR codes become invalid after scanning)
- Admin dashboard with attendance tracking
- Export capabilities (CSV, JSON)

## Quick Start
1. The server is already running on http://localhost:3000
2. Upload your Excel file with 'name' and 'id' columns
3. Use the scanner at http://localhost:3000/scanner
4. Monitor attendance at http://localhost:3000/admin

## File Structure
- server.js - Main Express server
- views/ - EJS templates for web interface
- public/ - Static files and generated QR codes
- sample-attendees.csv - Example data format

---
> Source: [geno543/qr_code_system](https://github.com/geno543/qr_code_system) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
