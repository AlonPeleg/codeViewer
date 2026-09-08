# Code Viewer & Compare

A lightweight, zero-dependency, single-file web application for viewing, syntax highlighting, auto-detecting, and comparing code snippets across dozens of programming languages.

![Code Viewer & Compare](https://img.shields.io/badge/Dependencies-Zero-brightgreen)

## 🌐 Live Demo

Try the live application hosted directly via GitHub Pages:  
👉 **[https://alonpeleg.github.io/codeViewer/](https://alonpeleg.github.io/codeViewer/)**

---

## ✨ Features

### 🔍 Code Viewer
* **Automatic Language Detection:** Uses pattern scoring to auto-detect over 20 programming languages with low/medium/high confidence indicators.
* **Manual Override:** Easily switch or override language syntax highlighting for any snippet.
* **Flexibility in Input:** Paste code directly or drop files directly into the upload/paste zone.
* **In-Page Search:** Fast text search within individual code snippets with result counting and smooth navigation.
* **Custom Layouts:** Switch between **Stack** and **Grid** view layout modes.
* **Snippet Controls:** Focus (maximize), wrap long lines, collapse/expand snippets, copy raw text, copy as Markdown code blocks, or download as files.
* **Local Persistence:** Snippets, overrides, and layouts persist across browser refreshes via `localStorage`.

### ⚖️ Code Comparison (Diff)
* **Dual Panel System:** Side-by-side Panel A vs. Panel B code editor.
* **Flexible Input:** Load snippets directly from the Viewer via one-click chips, context menus, or direct drag-and-drop.
* **Diff Engine:** Powered by an in-browser implementation of Myers' diff algorithm.
* **Multiple Display Modes:** 
  * **List View:** Clean line-by-line diff list with character-level inline highlighting.
  * **Side-by-Side View:** Collapsible side-by-side view highlighting additions, removals, and modifications.
* **Custom Filters:** Toggle options to ignore whitespace, ignore case, or ignore blank lines.
* **Synchronized Scrolling:** Synchronize scrolling across both comparison panels simultaneously.

---

## 🔤 Supported Languages

The application built-in detection and syntax highlighting supports:

* **Web & Markup:** HTML, CSS, XML, JSON, YAML
* **Scripting & Dynamic:** JavaScript, TypeScript, Python, Ruby, PHP, Shell (Bash)
* **Compiled & System:** Java, C#, C++, C, Go, Rust, Kotlin, Swift
* **Database & Enterprise:** SQL, InterSystems ObjectScript
* **Fallback:** Plain Text

---

## 🚀 Getting Started

Because the entire application is contained within a single `Code viewer.html` file, running it is completely friction-free:

### Option 1: Open Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/AlonPeleg/codeViewer.git](https://github.com/AlonPeleg/codeViewer.git)
