<div align="center">

# ✨ Zenith Colorscheme

<img src="https://raw.githubusercontent.com/samonide/zenith/main/assets/logo.svg" alt="Zenith Logo" width="120"/>

*A soothing, aesthetically pleasing colorscheme family with soft pastels*  
*Designed for comfortable long coding sessions with excellent readability*  
*Available in six beautiful variants: Dusk, Dawn, Twilight, Forest, Retro, and Ocean*

<p align="center">
  <a href="https://samonide.github.io/zenith/">
    <img src="https://img.shields.io/badge/🌐_Live_Preview-4A5568?style=for-the-badge&labelColor=1e1e2e&color=bba6f7" alt="Live Preview"/>
  </a>
  <a href="https://github.com/samonide/zenith">
    <img src="https://img.shields.io/badge/⭐_GitHub-4A5568?style=for-the-badge&labelColor=1e1e2e&color=89b4fa" alt="GitHub"/>
  </a>
  <a href="https://github.com/samonide/zenith/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-4A5568?style=for-the-badge&labelColor=1e1e2e&color=a6e3a1" alt="MIT License"/>
  </a>
</p>

<img src="https://img.shields.io/badge/Version-3.0.0-fab387?style=flat-square&labelColor=1e1e2e" alt="Version"/>
<img src="https://img.shields.io/badge/Variants-6-d5b8f5?style=flat-square&labelColor=1e1e2e" alt="Variants"/>

</div>

---

## ✨ Philosophy

<div align="center">

**Universal colorscheme base** that can be ported to any editor or application

</div>

- 🌙 **Deep, comfortable backgrounds** — Not pure black, easier on your eyes
- 🎨 **Soft pastel colors** — Gentle colors that don't strain
- 📖 **High readability** — Proper contrast where it matters
- 🔇 **Subtle UI elements** — Keep focus on your code
- 💫 **Soothing aesthetic** — Beautiful without being distracting

---

## 🎨 Variants

Zenith comes in six carefully crafted variants:

### 🌙 **Dusk** (Default)
The original Zenith experience - a soft pastel dark theme perfect for extended coding sessions. Balanced contrast with soothing colors that won't strain your eyes.

### ☀️ **Dawn**
A bright and airy light variant for daytime coding. Features gentle pastels on a light background while maintaining the Zenith aesthetic.

### 🌃 **Twilight**
A deeper, moodier dark variant for those late-night coding sessions. Enhanced depth with richer tones and lower brightness.

### 🌲 **Forest**
A calm dark theme with earthy green-gray tones. Perfect for natural, focused coding sessions with reduced eye strain.

### 🕹️ **Retro**
A nostalgic warm theme with vintage amber and sepia tones. Inspired by classic CRT terminals and vintage computing aesthetics.

### 🌊 **Ocean**
A serene deep blue theme inspired by calm ocean depths. Cool-toned with vibrant syntax colors for peaceful, focused coding.

---

## 📂 Structure

```
zenith/
├── colors.json         # Master palette with variant info
├── colors-dusk.json    # Dusk variant (default dark)
├── colors-dawn.json    # Dawn variant (light)
├── colors-twilight.json # Twilight variant (deeper dark)
├── colors-forest.json  # Forest variant (earthy green-gray)
├── colors-retro.json   # Retro variant (vintage warm)
├── colors-ocean.json   # Ocean variant (deep blue)
├── index.html          # Landing page & preview
├── README.md          # This file
└── implementations/   # Editor-specific implementations (coming soon)
    ├── vscode/       # VS Code theme
    └── neovim/       # Neovim colorscheme
```

---

## 🎨 Color Palette Example (Dusk Variant)

### Base Colors
| Name | Hex | Preview | Description |
|------|-----|---------|-------------|
| `bg` | `#1e1e2e` | ![#1e1e2e](https://via.placeholder.com/50x20/1e1e2e/1e1e2e.png) | Main background - deep purple-gray |
| `bgAlt` | `#252535` | ![#252535](https://via.placeholder.com/50x20/252535/252535.png) | Alternative background |
| `fg` | `#e0dfe8` | ![#e0dfe8](https://via.placeholder.com/50x20/e0dfe8/e0dfe8.png) | Main foreground text |
| `fgAlt` | `#b8b5c9` | ![#b8b5c9](https://via.placeholder.com/50x20/b8b5c9/b8b5c9.png) | Dimmed foreground |

### Syntax Colors
| Name | Hex | Preview | Usage |
|------|-----|---------|-------|
| `lavender` | `#bba6f7` | ![#bba6f7](https://via.placeholder.com/50x20/bba6f7/bba6f7.png) | Keywords, statements |
| `blue` | `#89b4fa` | ![#89b4fa](https://via.placeholder.com/50x20/89b4fa/89b4fa.png) | Functions, methods |
| `sky` | `#91d7e3` | ![#91d7e3](https://via.placeholder.com/50x20/91d7e3/91d7e3.png) | Types, classes |
| `cyan` | `#7dd4ed` | ![#7dd4ed](https://via.placeholder.com/50x20/7dd4ed/7dd4ed.png) | Operators |
| `green` | `#a6e3a1` | ![#a6e3a1](https://via.placeholder.com/50x20/a6e3a1/a6e3a1.png) | Strings, characters |
| `purple` | `#d5b8f5` | ![#d5b8f5](https://via.placeholder.com/50x20/d5b8f5/d5b5f5.png) | Variables, properties |
| `peach` | `#fab387` | ![#fab387](https://via.placeholder.com/50x20/fab387/fab387.png) | Constants, numbers |
| `red` | `#f5b5c8` | ![#f5b5c8](https://via.placeholder.com/50x20/f5b5c8/f5b5c8.png) | Errors, exceptions |

---

## 🚀 Getting Started

### Try it Out
1. **Live Preview**: Visit [samonide.github.io/zenith](https://samonide.github.io/zenith/)
2. **Switch Variants**: Click the buttons to see all 6 themes
3. **Choose Your Favorite**: Pick the one that suits your workflow

### Use the Colors
Each variant is stored in a JSON file with complete color definitions:
```json
{
  "name": "Zenith Dusk",
  "variant": "dusk",
  "type": "dark",
  "colors": { /* base, syntax, ui, git, diagnostic */ },
  "mapping": { /* semantic mappings */ }
}
```

---

## 🎯 Features

✨ **6 Unique Variants** — From light to dark, warm to cool  
🎨 **Consistent Design** — Same aesthetic across all themes  
👁️ **Eye Comfort** — Optimized for long coding sessions  
🌈 **Rich Syntax** — Distinct colors for better code reading  
⚡ **Smooth Transitions** — Beautiful theme switching on web  
📦 **JSON-Based** — Easy to port to any editor  

---

## 🚀 Preview

<div align="center">

### [**✨ View Live Demo**](https://samonide.github.io/zenith/)

Experience Zenith with live code examples and interactive theme switching!

*Or open `index.html` in your browser locally*

</div>

---

## 📦 Implementations

> 🚧 Coming soon! Zenith will be available for:

- 🎯 **VS Code** — Full theme with syntax highlighting and UI colors
- 🌙 **Neovim** — Lua-based colorscheme with TreeSitter support
- 🖥️ **Terminals** — iTerm2, Alacritty, Kitty, and more
- ⚡ **More editors** — Help us expand to your favorite editor!

Want to create an implementation? Check the JSON files for the complete color definitions!

---

<div align="center">

## 📄 License

MIT License — see [LICENSE](LICENSE) for details

## 💝 Contributing

Feel free to create implementations for other editors or suggest color improvements!  
**Star ⭐ the repo if you like Zenith!**

---

<sub>Made with 💜 by <a href="https://github.com/samonide">samonide</a></sub>

</div>
