# GloPose — project page

Source for the GloPose project page, served via GitHub Pages at
**https://tjelinek.github.io/glopose-page/**.

Built from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(Nerfies-derived). Static HTML/CSS/JS — no build step.

## Edit & deploy

Edit `index.html`, commit, and push to `main`; GitHub Pages redeploys automatically.

```bash
git add -A && git commit -m "Update page" && git push
```

## TODO before submission

Search `index.html` for `TODO(...)` markers:

- `TODO(name)` — finalize the project/paper name (currently the placeholder "GloPose"; the repo can be
  renamed later — GitHub auto-redirects the old URL).
- `TODO(authors)` / `TODO(affiliation/venue)` — full author list, affiliations, venue.
- `TODO(abstract)` — replace the draft with the paper abstract.
- `TODO(arxiv)` — arXiv id and PDF links.
- `TODO(bibtex)` — final BibTeX entry.
- `TODO(asset)` — teaser figure (`static/images/teaser.png`), a 1200×630 `social_preview.png`,
  and result carousel images/videos. The media sections are commented out in `index.html` until assets exist.

**Also replace `static/images/favicon.ico`** — the template ships with the template author's favicon.

## Layout

- `index.html` — the page.
- `static/{css,js,images,videos,pdfs}` — template assets.
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll processing).
