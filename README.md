# CodeSmith

<div align="center">
  <h1>CodeSmith</h1>
  <p><strong>Free Browser-Based AI Code Builder & Troubleshooter</strong><br>
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

You describe what you want (Python programs, web apps, data tools, CLI utilities, or anything custom), and the **multi-agent orchestrator + worker** system handles specification, code generation, automated testing, debugging, iteration, and delivers downloadable code.

**100% in your browser • No installation • No backend server**

## 🚀 Live Demo
**[👉 Open CodeSmith Now](https://khalecl.github.io/codesmith/)**

---

## 🔄 How CodeSmith Works

CodeSmith uses a powerful **multi-agent** architecture with a strong reasoning orchestrator (e.g. Kimi-K2) and specialized worker models.

### 1. Casual Chat → One-Block Tool

```mermaid
flowchart TD
    A[User describes project] --> B[Orchestrator: Kimi-K2]
    B --> C[Create Spec & Plan]
    C --> D[Worker: Devstral / Qwen]
    D --> E[Generate Code]
    E --> F[Test & Execute]
    F --> G{Works?}
    G -->|Yes| H[Download Package]
    G -->|No| I[Debug & Fix]
    I --> D
```

### 2. Advanced Multi-Agent Build Mechanism (Main Workflow)

```mermaid
flowchart TD
    User[User Description] --> Orchestrator[Orchestrator: Kimi-K2 Thinking]
    
    Orchestrator --> Needs[5-Why Analysis<br>Clarify Real Needs]
    Needs --> Skeleton[Skeleton / Architecture Design]
    
    Skeleton --> Worker1[Worker Agent 1<br>Build Block 1]
    Skeleton --> Worker2[Worker Agent 2<br>Build Block 2]
    Skeleton --> WorkerN[Worker Agent N<br>Build Block N]
    
    subgraph Testing Phase
        Worker1 --> Test1[Test Block 1<br>Record Output]
        Worker2 --> Test2[Test Block 2<br>Record Output]
        WorkerN --> TestN[Test Block N]
    end
    
    Test1 & Test2 & TestN --> Integration[Test Full Package]
    Integration --> Final{All Tests Pass?}
    Final -->|Yes| Package[Package + Download + Snapshots]
    Final -->|No| Debug[Debug & Iterate]
    Debug --> Orchestrator
```

### 3. Troubleshooting & Exploration Mode

```mermaid
flowchart LR
    Problem[User Problem<br>Python / WebApp / JS Bug] --> Explorer[Explorer Agent]
    Explorer --> Snapshot[Take Code Snapshot]
    Snapshot --> Analyze[Analyze + Draw Algorithm]
    Analyze --> Fix[Propose Fix]
    Fix --> Preview[Preview Changes]
    Preview --> Test[Run & Record Output]
    Test --> Validate{Works?}
    Validate -->|Yes| Result[Show Fixed Code + Explanation]
    Validate -->|No| Explorer
```

---

## Core Capabilities

- **Supported Project Types**:
  - 🐍 Python programs
  - 🌐 Web apps (HTML/JS)
  - 🧹 Data tools (CSV cleaners, analyzers)
  - 📁 CLI tools (file organizers, etc.)
  - ✨ Fully custom projects

- **Agentic Features**:
  - Natural language → detailed spec
  - Multi-agent skeleton design + block building
  - Automated testing & fixing loops
  - Code snapshots, output recording, algorithm diagrams
  - One-click project download

- **Model Flexibility** (OpenAI-compatible):
  - **NVIDIA Free Tier** (Recommended): Kimi-K2 Thinking (orchestrator) + Devstral worker — Best quality
  - **Groq Free Tier**: Fast Llama-4 Maverick + Qwen Coder
  - Bring Your Own Key (Anthropic, OpenAI, local, etc.)

## Quick Start

1. Open the [Live Demo](https://khalecl.github.io/codesmith/)
2. Choose a preset (**NVIDIA** or **Groq** for free use)
3. (Optional) Add your own API key
4. Describe your project or select a template
5. Watch the agents build → Download the result

**Pro tip**: Get free keys from [build.nvidia.com](https://build.nvidia.com) or [console.groq.com](https://console.groq.com)

---

## Tech Stack

- Pure frontend (single `index.html` + GitHub Pages)
- Custom NVIDIA proxy for reliable access
- Any OpenAI-compatible LLM backend
- Modern Tailwind UI + Mermaid diagrams

## Roadmap

- More templates and examples
- Improved multi-file project export (ZIP with structure)
- Better troubleshooting & algorithm visualization
- Future integrations (VS Code extension, etc.)

---

**Made with ❤️ by khalecl**  
**MIT License** — Free for personal and commercial use
