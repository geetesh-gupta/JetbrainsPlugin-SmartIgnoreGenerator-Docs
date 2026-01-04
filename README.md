[![Version](https://img.shields.io/jetbrains/plugin/v/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID)

<!-- Plugin description -->
# 🎯 Smart Ignore Generator

> **Never commit `node_modules/`, `.env`, or build artifacts again!**

**Smart Ignore Generator** is your intelligent assistant for creating optimized `.gitignore`, `.dockerignore`, and `.eslintignore` files. One right-click, and your project is protected with industry-standard ignore patterns.

## ✨ Why You'll Love It

### 🔍 **Zero Configuration**
Just right-click and go! The plugin automatically detects your project type and generates the perfect ignore files.

### 🧠 **Intelligent Detection**
Supports 10+ languages and frameworks:
- 🟢 **Node.js/JavaScript** - Never commit `node_modules/` again
- 🐍 **Python** - Keep `__pycache__/` and `.venv/` out
- ☕ **Java/Kotlin** - Ignore `target/`, `build/`, and `.class` files
- 🦀 **Rust** - Auto-ignore `target/` and `Cargo.lock`
- 🐹 **Go** - Clean repos without `vendor/`
- 💎 **Ruby** - Skip `.bundle/` and `vendor/`
- 🐘 **PHP** - Exclude `vendor/` from commits
- ⚙️ **C/C++** - Ignore build artifacts and binaries
- 🌐 **Multi-language** projects supported!

### 🛡️ **Smart & Safe**
- ✅ Detects existing files and asks before overwriting
- ✅ Industry-standard patterns from GitHub's gitignore repository
- ✅ Prevents common mistakes that plague beginners and pros alike

### ⚡ **Lightning Fast**
One click. Instant results. Professional-grade ignore files ready to go.

---

## 🚀 Features

- **Automatic Project Detection**: Intelligently detects your project type (Node.js, Python, Java, Kotlin, Go, Rust, C/C++, PHP, Ruby, or General)
- **Industry-Standard Templates**: Pre-configured with best practices from GitHub's official gitignore repository
- **Multi-Language Support**: Handles projects using multiple languages simultaneously
- **Smart Overwrite Protection**: Warns you before overwriting existing files with options to skip or overwrite
- **One-Click Generation**: Simple right-click action on any project directory

---

## 📦 What Gets Generated

| Language/Framework | Files Created |
|-------------------|---------------|
| **Node.js/JavaScript** | `.gitignore`, `.dockerignore`, `.eslintignore` |
| **Python** | `.gitignore`, `.dockerignore` |
| **Java** | `.gitignore`, `.dockerignore` |
| **Kotlin** | `.gitignore`, `.dockerignore` |
| **Go** | `.gitignore`, `.dockerignore` |
| **Rust** | `.gitignore`, `.dockerignore` |
| **C/C++** | `.gitignore`, `.dockerignore` |
| **PHP** | `.gitignore`, `.dockerignore` |
| **Ruby** | `.gitignore`, `.dockerignore` |
| **General/Multi-language** | `.gitignore` |

---

## 🎯 How to Use

### Step 1: Right-Click
Right-click on your project root directory in the **Project** view

### Step 2: Select Action
Choose **"Generate Optimized Ignore Files"** from the context menu

### Step 3: Done! 🎉
The plugin will:
- ✅ Detect your project type
- ✅ Generate appropriate ignore files
- ✅ Notify you of the results

**That's it!** Your ignore files are ready with industry-standard patterns.

---

## 💡 What Gets Ignored

### Common Patterns Across All Languages
- 🗂️ **IDE Files**: `.idea/`, `.vscode/`, `*.swp`
- 💻 **OS Files**: `.DS_Store`, `Thumbs.db`
- 🔐 **Environment**: `.env`, `.env.local`
- 📝 **Logs**: `*.log`

### Language-Specific Patterns
- **Node.js**: `node_modules/`, `dist/`, `build/`, `.next/`, `.cache/`
- **Python**: `__pycache__/`, `*.pyc`, `.venv/`, `*.egg-info/`
- **Java/Kotlin**: `target/`, `build/`, `*.class`, `.gradle/`
- **Rust**: `target/`, `Cargo.lock` (in libraries)
- **Go**: `vendor/`, `bin/`
- **And many more!**

---

## 🛡️ Prevents Common Mistakes

❌ **Before Smart Ignore Generator:**
```bash
git add .
# Oops! Just committed 500MB of node_modules/
# Leaked .env with production secrets
# Pushed build artifacts and IDE configs
```

✅ **After Smart Ignore Generator:**
```bash
git add .
# Only source code committed
# Secrets stay local
# Clean, professional repository
```

---

## 🎨 Beautiful Integration

- 🌓 **Theme-Aware Icons**: Gorgeous icons for both light and dark IDE themes
- 🔔 **Smart Notifications**: Clear feedback on what was generated
- 🎯 **Context-Aware**: Action only appears where it makes sense

---

## 🆓 Free & Open

This plugin is **completely free** with no limitations. Enjoy professional-grade ignore file generation without any paywalls!

---

## 🐛 Issues & Feedback

Have questions? Found a bug? Want to request a feature?

- 🐛 [Report Issues](https://github.com/geetesh-gupta/JetbrainsPlugin-SmartIgnoreGenerator-Docs/issues)
- 💡 [Request Features](https://github.com/geetesh-gupta/JetbrainsPlugin-SmartIgnoreGenerator-Docs/discussions)
- ⭐ [Star on GitHub](https://github.com/geetesh-gupta/JetbrainsPlugin-SmartIgnoreGenerator-Docs)

---

## 🙏 Support

If this plugin saves you time, consider:
- ⭐ Starring the repository
- 📝 Writing a review on the JetBrains Marketplace
- 📢 Sharing with fellow developers

---

**Made with ❤️ for developers who value clean repositories**

*Stop manually writing ignore files. Start building features.* 🚀
<!-- Plugin description end -->
