<div align="center">

# ✨ Zenith

**Premium colorscheme collection with 8 stunning variants**

[![Live Preview](https://img.shields.io/badge/🌐_Live_Preview-bba6f7?style=for-the-badge&labelColor=1e1e2e)](https://samonide.github.io/zenith/)
[![Version](https://img.shields.io/badge/v6.0.0-fab387?style=for-the-badge&labelColor=1e1e2e)](https://github.com/samonide/zenith)
[![License](https://img.shields.io/badge/MIT-a6e3a1?style=for-the-badge&labelColor=1e1e2e)](LICENSE)

*Soft pastels designed for comfortable long coding sessions*

</div>

---

## 🎨 Variants

**Eight professionally crafted themes, each with its own character:**

| Theme | Description |
|-------|-------------|
| 🌙 **Dusk** | Flagship theme with perfectly balanced soft pastels |
| ☀️ **Dawn** | Light theme with vibrant blues and gentle contrast |
| ✨ **Aurora** | Ethereal teals, pinks, and dreamy lavenders |
| 🌸 **Rosé** | Warm rose-tinted with cozy dark grey backgrounds |
| 🌊 **Ocean** | Deep serene blues and aqua tones for tranquil focus |
| 🌲 **Forest** | Natural vibrant greens for grounded productivity |
| 🌑 **Midnight** | Pure deep darkness with high contrast pastels |
| 🧘 **Zen** | Ultra-minimal monochrome for deep concentration |

---

## 🏗️ Architecture

Zenith uses the **[base46](https://github.com/NvChad/base46)** architecture — an industry-standard theming system designed for universal compatibility and portability across editors, terminals, and tools.

### Structure

Each theme contains two complementary color systems:

- **`base_30`** — 30 semantic color tokens defining backgrounds, UI elements, and syntax highlighting
- **`base_16`** — 16 standardized base16 colors for compatibility with base16-compatible applications

```json
{
  "base_30": {
    "white": "#e0dfe8",      // Primary text
    "black": "#1e1e2e",      // Main background
    "red": "#f38ba8",        // Error states
    "green": "#a6e3a1",      // Success states
    "blue": "#89b4fa",       // Primary accent
    "purple": "#bba6f7",     // Secondary accent
    // ... and 24 more semantic tokens
  },
  "base_16": {
    "base00": "#1e1e2e",     // Background
    "base05": "#e0dfe8",     // Foreground
    "base08": "#f38ba8",     // Variables
    "base0B": "#a6e3a1",     // Strings
    // ... and 12 more base16 colors
  }
}
```

This dual structure ensures Zenith works seamlessly across different environments while maintaining its unique aesthetic.

> 💡 **Inspiration:** Architecture inspired by [NvChad's base46](https://github.com/NvChad/base46) — the gold standard for portable colorscheme design.

---

## 🚀 Usage

**Live Preview:** Experience all themes at [samonide.github.io/zenith](https://samonide.github.io/zenith/)

**For Developers:** Load JSON files and map colors to your editor/terminal theme format

**VS Code Users:** Install [zenith-vsc extension](https://github.com/samonide/zenith-vsc)

---

## ✨ Features

- 🎨 **8 Unique Variants** — Professional themes for every mood and time of day
- 🏗️ **Base46 Architecture** — Industry-standard structure for universal portability
- 👁️ **Eye Comfort First** — Optimized for marathon coding sessions without strain
- 🌈 **Distinct Syntax Colors** — Carefully chosen for maximum code differentiation
- 📦 **JSON-Based** — Easy to parse, port, and implement in any environment
- ⚡ **Universal Compatibility** — Works with any tool that supports base16/base46

---

**Preview:** Open [samonide.github.io/zenith](https://samonide.github.io/zenith/) or `index.html` locally

**Implement:** Load JSON files and map colors to your editor's theme format

**VS Code:** [zenith-vsc extension](https://github.com/samonide/zenith-vsc)

---

## 📄 License

MIT License — see [LICENSE](LICENSE)

---

<div align="center">

*Made with 💜 by [samonide](https://github.com/samonide)*

</div>

