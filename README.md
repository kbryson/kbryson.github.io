# Academic profile site — Dr Kevin Bryson

Jekyll site for GitHub Pages: About / Research / Publications / Software / Teaching.
Content compiled from the public University of Glasgow staff page, Enlighten (ORCID-linked), GitHub and the BioAI Research YouTube channel. Google Scholar, ORCID and LinkedIn block automated reading, so check the publication list against Scholar and add anything missing to `_data/publications.yml`.

## Images to add (assets/img/)

- `kevin-and-dogs.jpg` — photo with the dogs, shown at the top of the About page (hidden automatically until present).
- `kevin-bryson.jpg` — sidebar portrait (falls back to the GitHub avatar until present).
- `omics-integration.svg`, `histopathology.svg` — original illustrations already included; swap for real figures if you have rights to them.

## Deploy

The repo `kbryson/kbryson.github.io` already exists, so:

    git clone https://github.com/kbryson/kbryson.github.io.git
    # copy the contents of this folder over it (replace old files), then
    git add -A && git commit -m "New profile site" && git push

Then Settings → Pages → Source: Deploy from a branch, `main`, `/ (root)`.

## Edit

- `index.md`, `research.md`, `software.md`, `teaching.md` — pages (Markdown + a little HTML).
- `_data/publications.yml` — one entry per paper; grouped by year automatically.
- `assets/css/style.css` — styling (Arial/Helvetica throughout). `_layouts/default.html` — header, nav, sidebar.

## Run locally (optional)

    bundle install && bundle exec jekyll serve
