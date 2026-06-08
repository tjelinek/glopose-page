# Project page — *Dense Matchers for Dense Object Reconstruction*

Source for the project page (codebase: **GloPose**), served via GitHub Pages at
**https://tjelinek.github.io/glopose-page/**.

Paper: *Dense Matchers for Dense Object Reconstruction* — Tomáš Jelínek, Dmytro Mishkin, Jiří Matas
(Visual Recognition Group, CTU in Prague). Title/authors/abstract/BibTeX mirror the Overleaf paper.

Built from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(Nerfies-derived). Static HTML/CSS/JS — no build step.

## Edit & deploy

Edit `index.html`, commit, and push to `main`; GitHub Pages redeploys automatically.

```bash
git add -A && git commit -m "Update page" && git push
```

> Note: this repo's `origin` uses **SSH** (`git@github.com:tjelinek/glopose-page.git`) — the HTTPS
> credential helper wasn't working on this machine.

## TODO before submission

Search `index.html` for `TODO(...)` markers (title/authors/abstract/BibTeX are already filled from the paper):

- `TODO(venue)` — set the venue once decided (paper is a WACV 2026 submission; page omits it for now).
- `TODO(arxiv)` — arXiv id, and wire the **Paper**/**arXiv** buttons (currently `href="#"`).
- `TODO(bibtex)` — switch from the `@misc` preprint entry to the published `@inproceedings` on acceptance.
- `TODO(asset)` — teaser figure (`static/images/teaser.png`), a 1200×630 `social_preview.png`,
  and result carousel images/videos. Media sections are commented out in `index.html` until assets exist.
  Candidate source figures live in the paper repo: `glopose-paper/imgs/`, `glopose-paper/figs/`.
- `TODO(name)` — if the project is renamed, the repo can be renamed too (GitHub auto-redirects the old URL).

**Also replace `static/images/favicon.ico`** — the template ships with the template author's favicon.

## Layout

- `index.html` — the page.
- `static/{css,js,images,videos,pdfs}` — template assets.
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll processing).
