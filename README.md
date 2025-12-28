
***

# Study Scope

![Status](https://img.shields.io/badge/status-stable-green?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Size](https://img.shields.io/badge/size-%3C20kb-orange?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-zero-red?style=flat-square)

**A lightweight, offline-first clarity tool that turns raw syllabus text into actionable study priorities.**

Study Scope is a single-file web application designed to eliminate cognitive overload. It parses unstructured text (syllabi, raw notes, AI outputs) and allows you to instantly categorize content into **Must Study**, **Optional**, and **Ignore** buckets.

No accounts. No cloud database. No AI hallucinations. Just text processing and logic.

### 🔗 [Launch Web App](https://aliriyaj007.github.io/Study-Scope/)

---

## ⚡ Why This Exists

Students and self-learners often waste 40% of their study time filtering noise. Syllabi are cluttered, and AI-generated study plans are often unstructured walls of text.

**Study Scope solves the "What do I focus on?" problem.**

| **The Old Way** | **The Study Scope Way** |
| :--- | :--- |
| ❌ Staring at a 10-page PDF syllabus | ✅ Visual, interactive cards |
| ❌ Highlighting everything (everything looks important) | ✅ Strict prioritization (Must / Optional / Ignore) |
| ❌ Mental fatigue from filtering noise | ✅ "Hide Ignored" mode for laser focus |
| ❌ Dependent on internet/cloud tools | ✅ Runs offline, saves to LocalStorage |

---

## 🛠 Core Features

*   **Smart Parsing Engine:** Automatically detects and formats Markdown, Code Blocks, Tables, and Lists.
*   **AI-Ready:** Paste raw text directly from ChatGPT, Claude, Gemini, or DeepSeek—Study Scope formats it instantly.
*   **Zero-Latency Interface:** Built with Vanilla JS and DocumentFragments for high performance on low-end devices.
*   **Privacy First:** Data persists via `localStorage`. Nothing leaves your browser.
*   **Import/Export:**
    *   📥 Import `.txt`, `.md`, or Backup `.json`.
    *   📤 Export prioritized lists as `.txt` or `.html`.
*   **Theming:** 8 academic-focused themes (Dark, Sepia, Ocean, Midnight, etc.).

---

## 🚀 Getting Started

### Method 1: Use the Web App (Instant)
Click the link below to use the hosted version. It loads once and works offline thereafter via cache.
[**Open Study Scope**](https://aliriyaj007.github.io/Study-Scope/)

### Method 2: Local Installation (Offline Forever)
Since Study Scope is a single-file application, you can run it without a server.

1.  Download the repository or just the `index.html` file.
2.  Open `index.html` in Chrome, Firefox, Safari, or Edge.
3.  That's it.

### Method 3: For Developers (Self-Host)
```bash
# Clone the repository
git clone https://github.com/Aliriyaj007/Study-Scope.git

# Navigate to directory
cd Study-Scope

# Open in browser (Mac)
open index.html

# Open in browser (Linux)
xdg-open index.html
```

---

## 📖 Usage Workflow

1.  **Input:** Paste your syllabus, notes, or AI-generated roadmap into the input box.
    *   *Tip:* Study Scope recognizes Markdown headers (`#`), Lists (`-`), and Tables (`|`).
2.  **Analyze:** Click **"Analyze & Scope"**. The text is broken into interactive blocks.
3.  **Prioritize:**
    *   Click a block to select it.
    *   Use the toolbar or **Double-Click** the block to cycle colors:
        *   🟨 **Must Study** (High Priority)
        *   🟦 **Optional** (Medium Priority)
        *   ⬜ **Ignore** (Low Priority / Grayed Out)
4.  **Focus:** Toggle the **"Hide Ignored"** checkbox to view only actionable items.
5.  **Save:** Your progress saves automatically. Use **Backup (.json)** to move data between devices.

---

## 💻 Tech Stack

*   **HTML5 / CSS3:** Semantic markup and CSS Variables for theming.
*   **Vanilla JavaScript (ES6+):** No frameworks (React/Vue/Angular) to ensure longevity and zero build steps.
*   **Regex Engine:** Custom Markdown-to-HTML parser optimized for speed.

---

## 🤝 Contributing

This project is feature-complete for its intended purpose, but optimizations are welcome.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

**Note:** Please do not submit PRs that introduce build steps (npm/webpack) or external dependencies. The philosophy of this tool is **"View Source -> Run."**

---

## 👤 Author & Contact

**Riyajul Ali**  
*Open Source Developer & Technical Writer*

*   **GitHub:** [@Aliriyaj007](https://github.com/Aliriyaj007)
*   **Email:** [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)
*   **LinkedIn:** [Aliriyaj007](https://linkedin.com/in/Aliriyaj007)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

*Made with ❤️ and pure JavaScript.*
