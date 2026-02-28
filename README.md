# 🎮 Tetris

A sleek, single-file Tetris game built with vanilla HTML, CSS, and JavaScript. No dependencies. No build step. Just open and play.

![Tetris Screenshot](https://img.shields.io/badge/HTML-CSS-JS-00f5ff?style=flat-square)

## ✨ Features

- Classic Tetris gameplay with all 7 tetrominoes
- Ghost piece to preview drop position
- Hard drop & soft drop
- Wall kick rotation system
- Progressive difficulty (speed increases with level)
- High score saved to `localStorage`
- Retro cyberpunk visual style with grid, glow effects & scanlines

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `← →` | Move left / right |
| `↑` or `Z` | Rotate |
| `↓` | Soft drop |
| `Space` | Hard drop |
| `P` | Pause / Resume |

## 🚀 Getting Started

No installation required. Just open `index.html` in any modern browser:

```bash
git clone https://github.com/yourusername/tetris.git
cd tetris
open index.html   # macOS
# or just double-click index.html on Windows/Linux
```

Or serve it locally:

```bash
npx serve .
# then visit http://localhost:3000
```

## 📁 Project Structure

```
tetris/
└── index.html   # Everything in one file — HTML, CSS, and JS
```

## 🏆 Scoring

| Lines Cleared | Points |
|---------------|--------|
| 1 (Single) | 100 × level |
| 2 (Double) | 300 × level |
| 3 (Triple) | 500 × level |
| 4 (Tetris!) | 800 × level |
| Soft drop | +1 per cell |
| Hard drop | +2 per cell |

## 📄 License

MIT — free to use, modify, and share.
