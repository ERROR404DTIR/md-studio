<div align="center">

<p align="center"><img src="assets/readme-banner.svg" alt="Animated MD Studio Markdown preview banner" width="100%"></p>

<img src="assets/banner.svg" alt="MD Studio" width="100%">

### A professional Markdown editor that lives in one HTML file.

**[Open the live editor](https://error404dtir.github.io/md-studio/)**

</div>

---

## Features

- **Live preview** with split, editor-only and preview-only modes and synced scrolling
- **GitHub-flavored Markdown**: tables, task lists (click to toggle in the preview), strikethrough, autolinks
- **Syntax highlighting** for fenced code blocks, with one-click copy
- **Math** with KaTeX (`$E = mc^2$` and `$$ ... $$` blocks)
- **Diagrams** with Mermaid (flowcharts, sequence diagrams and more)
- **Multiple documents**, outline navigation and **autosave** in your browser
- **Find and replace** with case-sensitive and regex options
- **Smart editing**: list continuation, indent and outdent, wrap toggles, paste images
- **Export** to `.md`, standalone `.html`, PDF (print), or copy as HTML
- **Dark and light themes**, focus mode, RTL and LTR support (Persian and Arabic friendly)
- **Private by design**: nothing is uploaded, everything stays in `localStorage`

## Keyboard shortcuts

| Action | Shortcut |
| --- | --- |
| Bold / Italic | `Ctrl` + `B` / `I` |
| Insert link | `Ctrl` + `K` |
| Find and replace | `Ctrl` + `F` (next: `F3`) |
| Download .md | `Ctrl` + `S` |
| Cycle view mode | `Ctrl` + `E` |

## Run locally

No build step and no dependencies to install:

```bash
git clone https://github.com/ERROR404DTIR/md-studio.git
cd md-studio
python3 -m http.server 8000   # or just open index.html
```

## Deploy

The site is published with GitHub Pages from the `main` branch (root folder).

## Tech

Plain HTML, CSS and JavaScript. Rendering libraries are loaded from cdnjs: [marked](https://marked.js.org), [DOMPurify](https://github.com/cure53/DOMPurify), [highlight.js](https://highlightjs.org), and lazily [KaTeX](https://katex.org) and [Mermaid](https://mermaid.js.org).

## License

MIT