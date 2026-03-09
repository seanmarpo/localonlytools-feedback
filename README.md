# localonly.tools — Feedback & Feature Requests

This repository is the public issue tracker for **[localonly.tools](https://localonly.tools)** — a growing collection of privacy-first, browser-based utility tools.

This repo exists so anyone can report bugs, request new tools, and follow along on what's being worked on.

---

## Support the project

localonly.tools is free to use, has no ads, and never asks you to create an account. Every tool runs entirely in your browser — there's no server to pay for, just time and coffee.

If the tools save you time or give you peace of mind, consider [buying a coffee ☕](https://ko-fi.com/smarpo) to help keep the project going and new tools coming.

---

## What is localonly.tools?

localonly.tools is a suite of developer and power-user tools that run **entirely in your browser**. No data is ever uploaded to a server. No account required. No ads.

Every tool processes your files, text, and secrets locally — that means sensitive data like JWTs, private keys, PDFs, and credentials never leave your machine.

### Current tools

| Category | Tools |
|---|---|
| **Text & Code** | Text Diff, Formatter (JSON / YAML / XML / HTML / CSS), Regex Tester |
| **PDF** | PDF Merge, PDF Split, PDF Page Manager, PDF to Image, PDF Compress, PDF Redact |
| **Images** | Image Diff, Image Converter, Image Compressor, Image Resizer, Image Redact, Background Remover, Image OCR |
| **Security & Auth** | JWT Inspector, SAML Inspector, Encrypt / Decrypt, Hash Generator, RSA Key Generator, TOTP Generator |
| **Data & Files** | SQLite Viewer, Parquet Viewer, HAR Viewer, Hex Viewer, Exif Viewer |
| **Email** | Email Header Analyzer, Email Viewer (.eml / .msg) |
| **Utilities** | UUID Generator, QR Code Generator, Subnet Calculator, Clipboard Inspector, Audio to Text |

---

## How to submit feedback

### 🐛 Report a bug

Found something broken or behaving unexpectedly? Please [open a Bug Report](../../issues/new?template=bug-report.md) and include:

- Which tool is affected
- What you expected to happen vs. what actually happened
- Steps to reproduce
- Your browser and OS

> **Tip:** If you can share a sample file to reproduce the issue, make sure it contains no sensitive or personal data before attaching it.

### 💡 Request a new tool

Have an idea for a tool that would fit the local-only philosophy? [Open a Tool Request](../../issues/new?template=tool-request.md) and describe:

- What the tool should do
- The problem or use case it solves
- Why a local/private solution matters for this use case
- Any similar online tools you've used as a reference

---

## What makes a good tool request?

localonly.tools is focused on tools where **privacy genuinely matters** — cases where you'd hesitate to paste your data into a random website. The best requests tend to involve:

- Sensitive file formats (credentials, keys, tokens, personal documents)
- Data you'd rather not send to a third-party server
- Tasks that are repetitive enough to warrant a dedicated, fast, no-friction UI

General-purpose tools that don't involve sensitive data are less likely to be prioritised, but still worth submitting if the use case is compelling.

---

## Scope of this repo

This repository is **only** for feedback and feature tracking. It does not contain any source code for the site.

- ✅ Bug reports for existing tools
- ✅ Requests for new tools
- ✅ Usability feedback or suggestions
- ❌ Pull requests (there is no code to contribute to here)
- ❌ Support questions (open an issue and it'll be addressed there)
