# AGENTS.md — Styledex

Styledex is an open-source **design-style codex**: browse named design styles, open any one for a usable recipe — palette, typography, cross-category samples, and an AI-ready prompt. Bilingual (EN / 中文).

## Working in this repo
- **Single file, zero deps, zero build.** The whole app is `Styledex_prototype.html` (HTML/CSS/JS inline). Open it directly in a browser; no install step.
- **`index.html`** is just the GitHub Pages entry that redirects into the prototype.
- **Adding a style** is the most common change — it's one block of structured data. See [CONTRIBUTING.md](./CONTRIBUTING.md) for the exact fields.
- Keep it **single-file and dependency-free**. Don't introduce a framework, bundler, or heavy CDN deps.
- Style data lives natively in Chinese with an English mirror — keep both in sync.

## Conventions
- Cyber-terminal aesthetic; heavy visual effects sit behind the `FX` toggle so they can be turned off.
- All sample imagery is generated in CSS (no external images / no licensing).
- License: MIT — code and style data are open.

Demo: https://underdogynino.github.io/Styledex/
