<div align="center">

<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/c97b6a52-1869-4bc7-b6e6-4431080ac5c3" />

# Lumas

**A local-first Windows AI agent desktop application.**

[![Latest Release](https://img.shields.io/github/v/release/d0x-dev/Lumas?label=Latest%20Release&style=flat-square)](https://github.com/d0x-dev/Lumas/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-blue?style=flat-square)](#system-requirements)
[![Downloads](https://img.shields.io/github/downloads/d0x-dev/Lumas/total?style=flat-square)](https://github.com/d0x-dev/Lumas/releases)

[Download Latest Release](https://github.com/d0x-dev/Lumas/releases/latest) · [Release Notes](https://github.com/d0x-dev/Lumas/releases/tag/v1.0.0) · [Report an Issue](https://github.com/d0x-dev/Lumas/issues)

</div>

---

> **Distribution Notice**
> This repository distributes **official compiled Windows releases only** and powers Lumas's built-in automatic update checker. Application source code is closed-source and is not hosted here.

---

## Overview

Lumas is a desktop AI agent workspace built for Windows (`x64`) by **Dark (`@d0x-dev`) · DxV Studio**. Bring your own API keys or local model endpoints while keeping conversations, workspace files, credentials, and usage metrics stored locally on your machine.

---

## Download & Install

Get the latest Windows builds from the [**Releases**](https://github.com/d0x-dev/Lumas/releases/latest) page:

| Package | File Pattern | Best For |
| --- | --- | --- |
| **Windows Installer** | `Lumas-Setup-<version>.exe` | Most users — installs shortcuts and supports seamless one-click in-app updates |
| **Portable Build** | `Lumas-Portable-<version>.exe` | Running directly from a folder or USB drive without installation |

### Automatic Updates

- Lumas automatically checks **GitHub Releases** on launch and periodically every 4 hours while running.
- When a newer `Lumas-Setup-*.exe` release is published, Lumas downloads and verifies it in the background and shows **`Click here to update`** in the top titlebar.
- Clicking the update pill exits Lumas cleanly and launches the new installer.
- You can inspect update status, trigger manual checks, or toggle background checks anytime under **Settings → System → Updates**.

---

## Key Features

### Multi-Provider Model Support
- **62+ Built-In Presets & Custom Providers**: OpenAI, Anthropic, Google Gemini, OpenRouter, Ollama / local servers, and custom OpenAI-compatible APIs.
- **Model Discovery & Management**: Auto-discover available models, inspect capability support (Vision / Thinking), rotate multiple API keys on rate limits, and remove unwanted models per provider.

### Autonomous Workspace & Agent Tools
- **Flexible Project Context**: Work inside any local project folder or start standalone **No project** conversations tracked under **Recents**.
- **Execution Modes**: Switch per session between **Chat only**, **Agent** (approval prompts), **Autonomous**, and **Full access**.
- **Integrated Tooling**: PowerShell / CMD command runner, background long-running build monitoring, file edit diff review sidebar, built-in Agent Browser, MCP server connections, and reusable Skills & Workflows.

### Privacy, Stats & Productivity
- **Local-Only Storage**: API keys and custom headers are encrypted on-device via **Windows DPAPI**; sessions and token logs stay locally under `%APPDATA%\lumas-desktop`.
- **Usage & Profile Insights**: Track per-model tokens, requests, latencies, and a 12-week Profile activity heatmap under **Settings → Profile** and **Usage & Stats**.
- **Keyboard Shortcuts**:
  - `Ctrl+N` — New session
  - `Ctrl+K` — Search sessions
  - `Ctrl+B` — Toggle sidebar
  - `Ctrl+J` — Toggle activity & diff panel
  - `Ctrl+M` — Open model picker
  - `Ctrl+,` — Open Settings
  - `Ctrl+Shift+T` — Toggle light / dark theme

---

## System Requirements

- **OS**: Windows 10 or Windows 11 (64-bit / x64)
- **Network**: Required for cloud model providers and GitHub update checks (offline supported with local providers)

---

## Support & Feedback

Found a bug or want to request a feature? Please open an issue on the [**Issues**](https://github.com/d0x-dev/Lumas/issues) tab with your Windows version, Lumas version (**Settings → System → About & Diagnostics**), and steps to reproduce.

---

<div align="center">

Copyright © 2026 **Dark (`@d0x-dev`) · DxV Studio**. All rights reserved.

</div>
