# Lei Hou / 侯蕾 — Academic Website

A bilingual (中文 / English), responsive academic homepage in a Morandi editorial style.

## Files

- `index.html` — homepage
- `publications.html` — searchable publication list
- `styles.css` — visual design and responsive layout
- `script.js` — bilingual switching, navigation, animation, publication filtering
- `publications-data.js` — publication data snapshot
- `assets/profile.jpg` — portrait
- `assets/favicon.svg` — HL monogram favicon

## Preview locally

Open `index.html` directly in a browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository named `hhoulei.github.io` (recommended), or any repository name.
2. Upload all files in this folder to the repository root.
3. In GitHub: **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. If the repository is named `hhoulei.github.io`, the site will normally be available at `https://hhoulei.github.io/`.

## Updating publications

Edit `publications-data.js`. Each item has `year`, `month`, `type`, `venue`, and `title`; an optional `url` can point to a DOI or paper page.

Current publication data are a ResearchGate snapshot dated 2026-08-31 and include journal articles and preprints.
