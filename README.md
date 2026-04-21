# CodeSmith

**Browser-native AI Python code smith**  
Plain English → fully tested, packaged Python modules — 100% in your browser.

![CodeSmith](https://raw.githubusercontent.com/khalecl/codesmith/main/index.html) <!-- GitHub will render the live demo link -->

## What is CodeSmith?

A single-file, zero-install web app that turns natural-language descriptions into production-ready Python packages.  
The AI writes the code, runs `pytest`, automatically repairs failures, and delivers a clean ZIP with source, tests, docs, and `requirements.txt`.

**No backend • No installation • Runs instantly in Chrome/Edge/Firefox/Safari**

## How It Works (3 Stages)

1. **Stage A — Requirements**  
   Conversational dialogue gathers exact specs.

2. **Stage B — Skeleton**  
   AI designs modular architecture + Mermaid diagram. You review & approve.

3. **Stage C — Build**  
   Each module is coded → tested with pytest → repaired (up to 3×) → integrated.  
   Final artifacts include full package with `.gitignore`, `README.md`, and symbol table.

## Features

- Full Pyodide Python sandbox (`/workdir` virtual FS, `micropip` installs, `pytest`)
- Live code editing, test repair loop, escalation editor
- Mermaid skeleton diagrams
- Session persistence (IndexedDB)
- Debug panel (Ctrl+Shift+D) with REPL + file browser
- One-click ZIP export of complete package
- Onboarding, command palette, templates, telemetry
- Dark Tailwind UI + syntax highlighting

**Day 7 milestone** — full UI + sandbox + multi-module builder complete. AI wiring (Day 3) is live via any OpenAI-compatible endpoint (Groq, NVIDIA, etc.).

## Quick Start

1. Open **[index.html](https://khalecl.github.io/codesmith/)** (or raw GitHub URL)
2. (Optional) Enter your OpenAI-compatible API key in Settings
3. Describe what you want → watch the magic
4. Download the finished package

**Pro tip:** Press `Ctrl+Shift+D` anytime to open the debug sandbox.

## Tech Stack

- **Frontend:** Vanilla JS + Tailwind CSS (CDN)
- **Runtime:** Pyodide 0.27.7 + pytest + micropip
- **Storage:** IndexedDB
- **Dependencies:** highlight.js, JSZip, Mermaid
- **Zero build step** — entire app is one `index.html`

## Project Roadmap (self-documented in source)

- ✅ Day 1–2: UI + Pyodide sandbox  
- ✅ Day 3–7: Full builder pipeline  
- Next: GitHub Actions, VS Code extension, multi-language support

## Repository Structure (after these additions)
