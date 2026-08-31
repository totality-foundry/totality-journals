# totality-journals

One-off HTML docs, mockups, and design docs used when discussing product ideas — quick rich artifacts, no build step.

Live site: https://totality-foundry.github.io/totality-journals/

## Usage

- Drop a new self-contained `.html` file at the repo root (or a dated subfolder, e.g. `2026/08/some-doc.html`).
- Push to `main` — GitHub Pages serves everything in the repo root directly, no build/CI needed.
- Link to it as `https://totality-foundry.github.io/totality-journals/<path>.html`.

## Conventions

- Keep each doc self-contained (inline CSS/JS, or CDN links) — no shared build pipeline.
- Prefer descriptive kebab-case filenames: `2026-08-31-checkout-flow-mockup.html`.
- `index.html` is a simple index/landing page — add a link to each new doc there so things stay discoverable.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
