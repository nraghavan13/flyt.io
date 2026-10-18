# flyt.io

Static site for flyt.io, an independent investment advisory (healthtech first, deep tech opportunistically). Plain HTML and CSS, no build step, hosted on GitHub Pages.

- `index.html` — the single-page site (phase 1, informational)
- `styles.css` — styles; colors and fonts are tokens at the top under `:root`
- `favicon.svg`
- `.nojekyll` — tells GitHub Pages to serve files as-is
- `ROADMAP.md` — phases and deferred ideas

Design canvas: https://claude.ai/artifact/4VmLJsFymMQbGsP884nvET

## Run locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploy on GitHub Pages

1. Push to `main`.
2. In the repo on GitHub: **Settings → Pages → Build and deployment**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site is published at `https://<user>.github.io/<repo>/` within a minute or two.

### Custom domain (flyt.io)

1. In **Settings → Pages → Custom domain**, enter `flyt.io` (this adds a `CNAME` file to the repo).
2. At your DNS provider, add `A` records for `flyt.io` pointing to GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a `CNAME` record for `www` pointing to `<user>.github.io`.
3. After DNS resolves, tick **Enforce HTTPS**.
