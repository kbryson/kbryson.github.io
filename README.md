# Academic profile site — Dr Kevin Bryson

A small Jekyll site (About / Research / Publications / Teaching) for GitHub Pages.
Content was assembled from the public University of Glasgow staff page and Enlighten repository — please review before publishing.

## Deploy on GitHub Pages

1. Create a repository. For `https://USERNAME.github.io/` name it `USERNAME.github.io`;
   for `https://USERNAME.github.io/REPO/` use any name and set `baseurl: "/REPO"` in `_config.yml`.
2. Set `url:` in `_config.yml` to match, and add a portrait as `assets/img/kevin-bryson.jpg` (optional — the sidebar hides it if absent).
3. Push, then in the repo go to Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site builds automatically; no local Ruby needed.

## Edit content

- `index.md`, `research.md`, `teaching.md` — Markdown pages.
- `_data/publications.yml` — one entry per paper; the Publications page groups by year automatically.
- `assets/css/style.css` — styling. `_layouts/default.html` — header, nav, sidebar.

## Run locally (optional)

    bundle install
    bundle exec jekyll serve
