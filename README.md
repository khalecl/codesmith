<div align="center">
  <h1>
    <img src="https://raw.githubusercontent.com/khalecl/codesmith/main/assets/logo.png" width="64" height="64" alt="CodeSmith" style="vertical-align: middle; margin-right: 12px;">
    CodeSmith
  </h1>
  
  <p><strong>Browser-native AI Python code smith</strong><br>
  Plain English → fully tested, packaged Python modules.<br>
  <strong>100% in your browser • No install • No backend</strong></p>

  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/khalecl/codesmith/main/index.html">
    <img src="https://img.shields.io/badge/🚀_Open_Live_Demo-Click_Here-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo">
  </a>
  <a href="https://github.com/khalecl/codesmith/releases">
    <img src="https://img.shields.io/badge/Version-0.4.0-4f8cff?style=for-the-badge" alt="Version 0.4.0">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="MIT License">
  </a>
  <img src="https://img.shields.io/badge/Python-in_browser-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Pyodide">
  <img src="https://img.shields.io/badge/Powered_by-Pyodide-4B8BBE?style=for-the-badge" alt="Pyodide">

  <br><br>
  <img src="https://raw.githubusercontent.com/khalecl/codesmith/main/assets/screenshot-hero.png" width="800" alt="CodeSmith Hero Screenshot" style="border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
  
  <h3>Turn natural language into production-ready Python packages — instantly</h3>
</div>

---

## ✨ What is CodeSmith?

**CodeSmith** is a single-file, zero-dependency web app that lets you describe what you want in plain English and instantly get a complete, tested Python package back — all running 100% inside your browser using Pyodide.

No servers. No API keys required to start. Just open and build.

## 🚀 Live Demo (instant — no install)

[**👉 Open CodeSmith in your browser now**](https://htmlpreview.github.io/?https://raw.githubusercontent.com/khalecl/codesmith/main/index.html)

*(Pro tip: Press `Ctrl+Shift+D` anytime for the full debug sandbox)*

## Features

- 🧠 **Conversational AI builder** — Stage A requirements → Stage B architecture → Stage C code + auto-repair loop
- 🧪 **Full pytest + micropip sandbox** — real Python execution, package installs, test fixing
- 📊 **Live Mermaid architecture diagrams**
- 💾 **IndexedDB persistence** — your sessions survive browser restarts
- 📦 **One-click ZIP export** — complete package with tests, docs, and `requirements.txt`
- 🎨 **Beautiful dark Tailwind UI** + syntax highlighting + command palette
- 🔌 **Ready for any OpenAI-compatible endpoint** (Groq, OpenAI, etc.) — just paste your key

## Tech Stack (all in one file)

- Vanilla JS + Tailwind CSS (CDN)
- Pyodide 0.26+ + pytest + micropip
- highlight.js, JSZip, Mermaid
- **Zero build step** — the entire app *is* `index.html`

## Quick Start

1. Click the **Live Demo** button above
2. (Optional) Add your API key in ⚙️ Settings
3. Describe your idea in the chat
4. Watch it build → download the finished package

## Screenshots

*(Add your own screenshots here later — just drag images into the `assets/` folder and update the links)*

## Roadmap

- ✅ v0.4.0 — Full UI + Pyodide sandbox + multi-stage builder
- ⏳ v0.5.0 — GitHub Pages + examples gallery
- 🔜 AI model selector + VS Code extension

## Contributing

The app is deliberately kept as a single `index.html` to preserve the “instant open” magic. PRs that keep it single-file are especially welcome!

## License

MIT © 2026 khalecl — see [`LICENSE`](LICENSE) file.

---

**Made with ❤️ for the browser-first future**
