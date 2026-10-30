# NexusNote

> **Local-First, All-in-One Knowledge Workstation & WYSIWYG Document Studio.**

[![GitHub Release](https://img.shields.io/github/v/release/xtc002007/NexusNote?style=flat-square&color=teal)](https://github.com/xtc002007/NexusNote/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20x64-blue.svg?style=flat-square)](https://nexustools.tech)
[![WYSIWYG](https://img.shields.io/badge/editor-Milkdown%20Crepe%20(ProseMirror)-00b4d8.svg?style=flat-square)](https://milkdown.dev)
[![Engine](https://img.shields.io/badge/backend-Rust%20%7C%20Tauri%20v2-orange.svg?style=flat-square)](https://tauri.app)
[![License](https://img.shields.io/badge/license-Proprietary-lightgrey.svg?style=flat-square)](./LICENSE)

---

## 📌 Overview

**NexusNote** is a local-first, unified document management and knowledge authoring workstation designed for researchers, writers, academics, and knowledge architects. Combining a rich **What-You-See-Is-What-You-Get (WYSIWYG) Markdown editor** (built on Milkdown Crepe and ProseMirror) with a high-performance **Rust Document Engine**, NexusNote handles Markdown notes, multi-hundred-page PDF documents, technical schematics, and source code files inside one integrated desktop environment.

This repository serves as the **official public distribution and release portal** for NexusNote binaries, release notes, and package manager feeds (including [winget](https://github.com/microsoft/winget-pkgs)).

---

## ⚡ Key Highlights & Core Capabilities

### 1. Unified Multi-Format Document Center
- **Unified Document Pipeline**: Seamlessly open and organize `.md`, `.txt`, `.json`, `.yaml`, source code, `.pdf`, and visual assets (`.png`, `.jpg`, `.webp`, `.svg`) in a single workspace.
- **High-Performance PDF Viewer**: Powered by native **lopdf** and **Google PDFium**. Renders multi-hundred-page research papers and e-books through per-page WebP streaming and virtualized window scrolling—heavy PDF binaries never clog the frontend WebView memory.
- **Intelligent Image Engine**: Automatic EXIF orientation normalization, fast local thumbnail caching, on-demand zoom inspection, and raw SVG vector mode.

### 2. True WYSIWYG Editing with Source-Text Fidelity
- **Milkdown Crepe & ProseMirror Core**: Enjoy modern, friction-free WYSIWYG editing with block-level drag-and-drop handles, intuitive slash commands (`/heading`, `/table`, `/code`), and inline formatting menus.
- **100% Source-Text Fidelity**: Preserves standard CommonMark/GFM formatting under the hood. Documents created in NexusNote can be immediately opened in Obsidian, Typora, VS Code, or GitHub without syntax distortion.
- **Interactive Tables & Math**: Inline table editing and asynchronous **KaTeX** math formulas rendering smoothly in real-time.

### 3. Integrated Diagramming & 50+ Language Highlighting
- **Mermaid 11 Support**: Direct visualization of flowcharts, sequence diagrams, state machines, entity-relationship diagrams, and Gantt charts.
- **CodeMirror 6 Engine**: Embedded syntax-highlighted code blocks supporting over 50 programming, markup, and configuration languages.

### 4. Deep Workspace Search & SQLite FTS5 Indexing
- **Cross-Format Full-Text Search**: SQLite FTS5 engine indexes not only your Markdown notes and text files, but also extracts and indexes text content from PDF documents.
- **Instant Search Results**: Substring and boolean keyword filtering with live preview snippets and jump-to-location accuracy.

### 5. Curated Typography & Themes
- **11 Professional Themes**: Meticulously crafted typographic colorways tailored for long reading sessions, technical documentation, and nocturnal writing (featuring Light, Dark, Sepia, Nord, Dracula, and high-contrast modes).

---

## 🚀 Installation & Downloads

### Method 1: Windows Package Manager (winget) — Recommended

Install NexusNote via Windows Terminal or PowerShell:

```powershell
winget install NexusTools.NexusNote
```

Upgrade to the latest version:

```powershell
winget upgrade NexusTools.NexusNote
```

---

### Method 2: Direct Download from GitHub Releases

Visit the [GitHub Releases](https://github.com/xtc002007/NexusNote/releases/latest) page to download official packages:

| Asset | Description | Recommended For |
| :--- | :--- | :--- |
| `NexusNote_<version>_windows_x64_setup.exe` | Standard Windows NSIS Installer | General desktop installation (includes auto-updater) |
| `NexusNote_<version>_windows_x64_portable.zip` | Standalone Portable Archive | Portable drives & zero-install workflows |

---

### Method 3: Official NexusTools Suite

Download NexusNote directly from the [NexusTools Official Portal](https://nexustools.tech).

---

## 🔒 Security, Authenticity & Verification

- **Code Signing**: All executables are signed with Windows Authenticode digital certificates.
- **Cryptographic Signatures**: Minisign Ed25519 signatures (`.sig`) are provided for every setup installer.
- **Silent Background Updates**: In-app updater securely checks official NexusTools endpoints over TLS 1.3 with cryptographic verification.

---

## ⚖️ License & EULA

NexusNote is distributed under the [NexusTools End-User License Agreement (EULA)](./LICENSE).  
- Core local note-taking, WYSIWYG editing, PDF reading, and FTS5 search are permanently free for personal and commercial usage.  
- Optional cloud AI writing assistance and cross-device sync require a NexusTools subscription.

---

## 💬 Community & Support

- **Bug Reports & Issues**: [GitHub Issues](https://github.com/xtc002007/NexusNote/issues)
- **Official Portal**: [https://nexustools.tech](https://nexustools.tech)
