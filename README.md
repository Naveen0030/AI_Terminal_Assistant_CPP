# 🧠 Terminal AI Assistant (Offline GPT with Ollama)

A lightweight C++ terminal-based AI assistant using local LLMs via the [Ollama](https://ollama.com) API.

---

### 🔧 Features

- 💻 Terminal-based chat UI
- 🤖 Local inference with Ollama models (no internet needed after setup)
- 📦 Uses only:
  - `libcurl` (for HTTP requests)
  - `nlohmann/json` (for JSON parsing)
- 🎨 ANSI-colored terminal output
- ✅ Fully works on **Windows**, without needing `vcpkg` or Visual Studio

---

### 🚀 Setup Guide (Windows)

#### 1. ✅ Install [Ollama](https://ollama.com/download)
After installation, run it once:
```bash
ollama run llama3
```
This downloads and runs the model locally via http://localhost:11434.

ℹ️ Ollama must be running in the background before starting the assistant.
