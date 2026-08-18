# 🎨 Pixel Art Editor / Піксельний Арт Редактор

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://pixelarteditor.github.io)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A beautiful grid-based pixel art drawing tool with a rich color palette, modern drawing instruments, magic wizards, symmetry & mirror modes, image import, 100-step undo/redo, and one-click PNG export. Fully bilingual (🇺🇦 Ukrainian by default / 🇬🇧 English) with automatic state persistence and support for both horizontal and vertical layouts. Start creating pixel masterpieces right in your browser!

<p align="center">
  <a href="https://pixelarteditor.github.io">
    <img src="https://img.shields.io/badge/🎨%20Live%20Demo-Click%20Here-e94560?style=for-the-badge" alt="Live Demo">
  </a>
</p>

---

## ✨ Features

### 🖌️ Drawing Tools
- **✏️ Pen** - Draw individual pixels with the current color
- **🧽 Eraser** - Remove pixels cleanly
- **🪣 Fill (Bucket)** - Flood-fill connected areas
- **💧 Color Picker** - Sample any color directly from the canvas
- **📏 Line** - Draw straight lines with live preview
- **▭ Rectangle** - Draw outlined rectangles
- **⬭ Circle / Ellipse** - Draw circular and elliptical shapes
- **💨 Spray** - Airbrush effect with random pixel scattering
- **🌗 Shade** - Progressively darken existing pixels for shadows & depth

### 🎨 Color & Palette
- **18-color starter palette** with popular pixel-art tones
- **Custom color picker** — add any color you like
- **Add / remove swatches** (double-click a swatch to delete)
- **Active color highlighting** for quick reference

### 🪄 Advanced Features
- **↔ Mirror X / ↕ Mirror Y** - Draw symmetrically across one or both axes
- **Adjustable Brush Size** - From 1px up to 6px
- **🖼️ Image Import** - Load any image and pixelate it onto the grid
  - **🔁 Replace** — clear the canvas and insert the image
  - **➕ Add on top** — overlay onto your current drawing
  - Aspect-ratio preserved, transparent pixels skipped

### 🧙 Magic Wizards
| Wizard | Description |
|--------|-------------|
| 🏁 **Checkerboard** | Fill the canvas with a two-color checker pattern |
| 🌈 **Gradient** | Smooth horizontal color transition |
| 🖼️ **Frame** | Draw an outline border around the canvas |
| ✨ **Noise / Stars** | Scatter random pixels for starfields & texture |
| 🎞️ **Dithering** | Blend two colors in a classic dither pattern |
| 🔮 **Symmetry** | Mirror one half of the artwork onto the other |
| 🔄 **Invert** | Invert all pixel colors |
| 🎨 **Rainbow** | Colorize rows in a full rainbow spectrum |

### 🌐 Localization
- **🇺🇦 Ukrainian** (default language)
- **🇬🇧 English**
- Instant language switching — every label updates live

### 💾 Persistent State
- All artwork, palette, tool, brush, grid size, orientation & language saved in **localStorage**
- Everything restored automatically on page reload

### ↩️ History
- **100-step Undo / Redo** with smart duplicate detection
- Auto-disabling buttons + live step counter
- Keyboard shortcuts included

### 📐 Layout & Export
- **Horizontal & Vertical** orientation modes
- **Responsive 3-zone desktop layout** that gracefully collapses on tablets & mobile
- Adjustable grid size from **4×4 up to 80×80**
- **💾 Export to PNG** at 20× scale for crisp, shareable pixel art
- **Native-style confirm dialogs** with smooth animations

---

## 🎮 Controls

### Mouse & Touch
| Action | Result |
|--------|--------|
| **Click / Tap** | Draw with the active tool |
| **Click & Drag** | Continuous drawing (smooth stroke interpolation) |
| **Drag (Line/Rect/Circle)** | Live shape preview until release |
| **Double-click swatch** | Remove color from palette |

### Buttons
| Button | Function |
|--------|----------|
| 🧙 **Wizards** | Open the magic effects & generators |
| 🖼️ **Load Image** | Import an image (Replace or Add mode) |
| ↩️ **Undo** / ↪️ **Redo** | Step through history (up to 100 steps) |
| 🗑️ **Clear** | Clear the entire canvas (with confirm dialog) |
| 💾 **PNG** | Export your artwork as a PNG file |
| ↔ / ↕ **Orientation** | Switch between horizontal & vertical layout |
| **УКР / EN** | Toggle interface language |

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `B` | Select Pen tool |
| `E` | Select Eraser tool |
| `G` | Select Fill (bucket) tool |
| `Ctrl/⌘ + Z` | Undo |
| `Ctrl/⌘ + Y` or `Ctrl/⌘ + Shift + Z` | Redo |

---

## ⚙️ Customization Options

| Setting | Range | Description |
|---------|-------|-------------|
| **Grid Width** | 4 - 80 | Number of horizontal cells |
| **Grid Height** | 4 - 80 | Number of vertical cells |
| **Brush Size** | 1 - 6 | Pixel radius of the brush |
| **Mirror X** | On / Off | Horizontal symmetry drawing |
| **Mirror Y** | On / Off | Vertical symmetry drawing |
| **Orientation** | Horizontal / Vertical | UI panel layout arrangement |
| **Language** | UK / EN | Interface language |

---

## 🚀 Quick Start

### Option 1: Visit Live Demo
Simply go to **[https://pixelarteditor.github.io](https://pixelarteditor.github.io)**

### Option 2: Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/pixelarteditor/pixelarteditor.github.io.git
   ```

2. **Navigate to directory**
   ```bash
   cd pixelarteditor.github.io
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html        # macOS
   start index.html       # Windows
   xdg-open index.html    # Linux
   ```

> **Note:** No build step, dependencies, or server required — it's a single self-contained HTML file!

---

## 📁 Project Structure

```
pixelarteditor.github.io/
│
├── index.html          # Main application (all-in-one HTML/CSS/JS)
├── README.md           # Documentation
├── LICENSE             # MIT License
└── .gitignore          # Git ignore file
```

---

## 🛠️ Technologies

| Technology | Purpose |
|------------|---------|
| **HTML5 Canvas** | Rendering the pixel grid & artwork |
| **CSS3** | Styling, responsive layout, modal animations |
| **Vanilla JavaScript** | Drawing logic, tools, state management |
| **FileReader API** | Loading & importing user images |
| **localStorage API** | Persistent state & artwork saving |
| **SVG** | Inline favicon (colorful pixel grid) |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
   ```bash
   git fork https://github.com/pixelarteditor/pixelarteditor.github.io.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Commit your changes**
   ```bash
   git commit -m "Add amazing feature"
   ```

4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```

5. **Open a Pull Request**

### Ideas for Contributions
- [ ] Animation frames / GIF export
- [ ] Multiple layers support
- [ ] More export formats (SVG, JSON sprite sheet)
- [ ] Additional wizards & effects
- [ ] Custom palette import/export
- [ ] Onion-skinning for animation
- [ ] Zoom & pan on large canvases
- [ ] More languages (Polish, German, Spanish...)
- [ ] Keyboard color-cycling
- [ ] Cloud save / shareable links

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Inspired by classic pixel art & sprite editors
- Built with modern web technologies
- Thanks to the open-source community

---

## 📧 Contact

- **Repository**: [github.com/pixelarteditor/pixelarteditor.github.io](https://github.com/pixelarteditor/pixelarteditor.github.io)
- **Live Demo**: [pixelarteditor.github.io](https://pixelarteditor.github.io)
- **Issues**: [Report a bug](https://github.com/pixelarteditor/pixelarteditor.github.io/issues)

---

<p align="center">
  Made with ❤️ and 🎨
  <br><br>
  <a href="https://pixelarteditor.github.io">
    <img src="https://img.shields.io/badge/🎨%20Start%20Drawing-NOW-e94560?style=for-the-badge" alt="Start Drawing">
  </a>
</p>

---

⭐ **Star this repo if you enjoyed creating pixel art!** ⭐
