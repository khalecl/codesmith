<div align="center">
  <h1>CodeSmith</h1>
  <p><strong>Free browser-based AI Code Builder & Troubleshooter</strong><br>
  Describe → Spec → Build → Test → Fix → Download</p>

  <a href="https://khalecl.github.io/codesmith/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_Now-4f8cff?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://github.com/khalecl/codesmith">
    <img src="https://img.shields.io/badge/Version-v0.1.0-blue?style=for-the-badge" alt="Version">
  </a>
</div>

---

## ✨ What is CodeSmith?

**CodeSmith** is a free, open-source web app that turns natural language descriptions into complete, working projects. 

You describe what you want (Python scripts, web apps, data tools, CLI utilities, etc.), and the AI **orchestrator + worker** system handles specification, code generation, testing, debugging, and iteration — then gives you downloadable code.

**No installation required. Runs entirely in your browser.**

## 🚀 Live Demo
**[👉 Open CodeSmith](https://khalecl.github.io/codesmith/)**

## Core Capabilities (Current)

- **Multi-language & Project Support**:
  - Python programs
  - Web apps (HTML/JS)
  - Data tools (CSV cleaners, analyzers)
  - CLI tools (file organizers, etc.)
  - Fully custom projects

- **Agentic Workflow**:
  - Natural language → detailed spec
  - Code generation
  - Automated testing & fixing loops
  - Iteration until it works

- **Model Flexibility** (OpenAI-compatible):
  - **NVIDIA Free Tier**: Kimi-K2 Thinking (orchestrator) + Devstral worker (best quality)
  - **Groq Free Tier**: Fast Llama-4 + Qwen Coder
  - Bring Your Own Key (Anthropic, OpenAI, local, etc.)

- **Proxy Support**: Built-in reliable NVIDIA proxy for stable access

## Quick Start

1. Open the [live demo](https://khalecl.github.io/codesmith/)
2. Choose a preset (NVIDIA or Groq recommended for free use)
3. (Optional) Add your own API key
4. Describe your project in the chat
5. Download the complete result

## Features

- Chat / Build / Explore interface
- Pre-built templates (Data Cleaner, Text Analyzer, File Organizer)
- Custom agentic mode with full iteration
- Multiple model presets
- One-click download of generated projects

## Tech Stack

- Pure frontend (GitHub Pages)
- Custom NVIDIA proxy
- Any OpenAI-compatible LLM backend
- Modern UI with Tailwind

## Roadmap

- Expanded templates & examples
- Better multi-file project support
- Export options (ZIP, GitHub repo init)
- VS Code / Cursor integration (future)

---

**Made with ❤️ by khalecl**

MIT License • Free forever for personal & commercial use
