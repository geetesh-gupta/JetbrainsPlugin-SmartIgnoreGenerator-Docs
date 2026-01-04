# 🚀 SmartIgnoreGenerator Changelog

All notable changes to the **Smart Ignore Generator** plugin will be documented in this file.

---

## [Unreleased]

## [2026.1.1]

### ✨ Initial Release - Never Commit `node_modules/` Again!

The first public release of Smart Ignore Generator is here! Say goodbye to manually writing `.gitignore` files and hello to intelligent, one-click ignore file generation.

#### 🎯 Core Features

- **🔍 Intelligent Project Detection**: Automatically identifies your project type by analyzing characteristic files
  - Supports 10+ languages: Node.js, Python, Java, Kotlin, Go, Rust, C/C++, PHP, Ruby, and more
  - Handles multi-language projects seamlessly
  
- **📝 Industry-Standard Templates**: Pre-loaded with battle-tested ignore patterns
  - `.gitignore` - Keep your repos clean
  - `.dockerignore` - Optimize your Docker builds
  - `.eslintignore` - For JavaScript/TypeScript projects
  
- **🛡️ Smart Overwrite Protection**: Never lose existing configurations
  - Detects existing ignore files
  - Offers clear choices: Overwrite All, Skip Existing, or Cancel
  - Full control in your hands

- **⚡ One-Click Generation**: Simply right-click any project directory
  - No configuration needed
  - Instant results
  - Clear success notifications

- **📦 What's Included**:
  - 24+ pre-configured ignore file templates
  - Support for 10 major programming languages
  - Multi-language project detection
  - Context menu integration in Project view

---

### 🔜 Coming Soon

We're always improving! Here's what's on the roadmap:

#### v2026.2.1 - Smart Pattern Scanning (Planned)

- 🔍 **Scan for Additional Patterns**: Optional feature to detect project-specific files to ignore
  - Explicit user trigger (not automatic - you stay in control!)
  - Conservative suggestions only (we won't suggest ignoring your source code)
  - Clear explanations for each suggestion (so you know why)
  - Easy accept/reject interface (pick what you want)
  - Examples: `*.log`, `*.tmp`, `*.db`, `.DS_Store`, large binaries

#### Future Enhancements

- 🎨 Customizable templates
- 🌍 More language support (Swift, Dart, Elixir, Scala, etc.)
- ⚙️ Settings UI for template customization
- 📊 Template versioning and updates
