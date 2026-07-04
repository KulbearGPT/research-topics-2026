# Student AI Research Topics

Static bilingual website for student AI research topic selection.

The site includes:
- Chinese and English homepages: `index.html`, `index_en.html`
- 3D AI research topics around 3D Gaussian reconstruction, rigging, and deformation
- AI for Social Impact topics around medical imaging, wildfire prediction, and urban flood risk
- Generated local teaser images under `assets/`

## GitHub Pages

This is a plain static site. No build step is required.

Recommended GitHub Pages settings:
1. Push this repository to GitHub.
2. Open repository `Settings` -> `Pages`.
3. Set `Build and deployment` source to `GitHub Actions`.
4. The workflow in `.github/workflows/pages.yml` will publish the static site from `main`.
5. The published site will use `index.html` as the default Chinese homepage.

The English homepage is available at:

```text
index_en.html
```

## Local Preview

Open `index.html` directly in a browser, or use any static server from this directory.

## Notes

- `.nojekyll` is included so GitHub Pages serves static assets directly.
- External research images are used only as visual references.
- Generated teaser images are local project assets.
