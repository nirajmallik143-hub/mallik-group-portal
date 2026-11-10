<div align="center">

# 🚀 Mallik Group Ecosystem

*Building robust, lightweight digital ecosystems entirely mobile-first.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Mobile-First](https://img.shields.io/badge/Environment-Termux%20%2F%20Android-blueviolet)](https://termux.dev)
[![Status](https://img.shields.io/badge/Status-Active%20Development-success)](https://github.com/nirajmallik143-hub)

</div>

---

## 🏗️ Core Architecture & Tech Stack

Our development philosophy centers around zero-bloat, client-side resilience, and agile on-device execution. 

```text
[ Mobile Environment (Termux / Acode / Pydroid 3) ]
                       │
                       ▼
[ Unified Python Backend (Flask / Node / dotenv Security) ]
         │             │               │
         ▼             ▼               ▼
   [ Gemini API ] [ DeepSeek API ] [ GitHub API ]
         │             │               │
         └─────────────┼───────────────┘
                       │
                       ▼
    [ Single-File PWAs & Client-Side Dashboards ]
```

### 1. The Mobile-First Development Environment
* **On-Device Execution:** Entirely built, tested, and maintained on Android mobile environments using **Termux**, **Acode**, and **Pydroid 3**.
* **Version Control & CI/CD:** Direct repository management, automated commits, and deployment via GitHub workflows.

### 2. Unified API Gateway & Secret Management
* **Secure Configuration:** Environment variables (`GEMINI_API_KEY`, `DEEPSEEK_API_KEY`, `GITHUB_TOKEN`) are securely managed via local `.env` loaders (`python-dotenv`), ensuring strict separation of concerns on mobile execution layers.
* **Multi-Model Routing:** Integrated REST endpoints that route intelligence tasks dynamically between **Gemini 1.5 Flash**, **DeepSeek**, and custom analytical nodes.

### 3. Frontend & Delivery Layer
* **Single-File PWAs:** Optimized HTML5, modern CSS3, and vanilla JavaScript bundled into standalone Progressive Web Apps for instant loading and offline-first capabilities.

---

## 🚀 Ecosystem Projects

### 📱 Sikshya AI
* **Description:** A trilingual educational platform and AI tutoring agent designed to democratize accessible learning tools across multiple languages.
* **Architecture:** Client-side interactive UI powered by dynamic prompt routing through our unified API gateway.

### ♻️ EcoThread (`nirajmallik143-hub/EcoThread`)
* **Description:** A carbon-aware code optimizer that profiles Abstract Syntax Trees (ASTs) and refactors Python code to reduce computational overhead and energy consumption.
* **Architecture:** Static code analysis engine running in Python execution environments.

### 🔒 Security & Operations Hub (`nirajmallik143-hub/nmdc-conduct-register`)
* **Description:** Field-tested mobile security management applications—including camp conduct registers, material logs, and operations dashboards.
* **Architecture:** Lightweight local state management with responsive layouts tailored for operational staff on duty.

---

## 📜 Licensing & Copyright

All repositories and software assets published under **Mallik Group** (`nirajmallik143-hub`) are licensed under the **MIT License**.

```text
MIT License

Copyright (c) 2026 Niraj Mallik (Mallik Group)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
