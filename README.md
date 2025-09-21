# GitHub Pages — Project Pages Starter

This repo publishes to `https://<username>.github.io/<repo>/` using GitHub Pages.

## Quick start
1) Put your site files at repo root (this includes `index.html`).
2) Push to GitHub:
```bash
git init
git add .
git commit -m "publish: initial site"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```
3) On GitHub → Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / root → Save.
4) Your site will be live at `https://<username>.github.io/<repo>/`.

> Keep `.nojekyll` if you use folders starting with `_`.
