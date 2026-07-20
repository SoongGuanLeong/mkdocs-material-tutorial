# MkDocs Material Tutorial

A personal reference project showcasing features of the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) documentation theme — a modern static site generator for project documentation.

## Demo

<!-- TODO: Replace with actual GitHub Pages URL once deployed -->
The live site is deployed via GitHub Pages: `https://SoongGuanLeong.github.io/mkdocs-material-tutorial/`

## Features Covered

- **Admonitions** — Callout boxes (notes, warnings, info) with collapsible support
- **Code Examples** — Syntax highlighting, line numbers, highlighted lines, code titles
- **Content Tabs** — Tabbed content blocks for multi-language or multi-format examples
- **Diagrams** — Mermaid.js diagrams (flowcharts, sequence diagrams) rendered inline
- **Theme Customization** — Dark/light mode toggle, custom fonts, color palettes, custom logo

## Quick Start

```bash
# Install dependencies
uv sync

# Start the development server
mkdocs serve
```

Open `http://127.0.0.1:8000` to preview.

## Build

```bash
mkdocs build
```

Output is written to the `site/` directory.

## Deployment

Automatic deployment to GitHub Pages via GitHub Actions. Push to `main` to trigger the workflow defined in `.github/workflows/ci.yml`.

## Requirements

- Python 3.12+
- [uv](https://docs.astral.sh/uv/) (package manager)

## License

MIT
