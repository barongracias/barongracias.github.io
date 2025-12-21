# barongracias.github.io

Professional services landing site built with Jekyll and the Minimal Mistakes remote theme. Copy is geared toward data/AI consulting, with service-to-proof links and a Contact anchor for fast outreach.

## Structure
- `_config.yml` — site metadata, theme options, plugins.
- `_pages/` — standalone pages (about, services, projects, mentorship, etc.).
- `_posts/` — dated blog posts with front matter.
- `_data/` — navigation, authors, and other YAML-driven settings.
- `assets/` and `files/` — images, downloads, and other static content.
- `_site/` — generated output for local builds (GitHub Pages will rebuild from source).

## UX notes
- Homepage (`index.md`) carries the hero, services-at-a-glance, results row (links to key projects), featured builds, and contact CTA.
- Services page links directly to relevant project write-ups for proof.
- Navigation includes a `/#contact` anchor for quick email access; mentorship remains a separate track.
- Visual system lives in `assets/css/main.scss` (Space Grotesk, teal/blue gradients, soft cards/buttons).

## Run locally
Prerequisites: Ruby + Bundler.
```bash
bundle install
bundle exec jekyll serve --livereload
# open http://localhost:4000
```
Stop and restart the server after changing `_config.yml` or installing new gems.
If your network blocks remote themes (SSL interception), run with the local override:  
`bundle exec jekyll serve --livereload --config _config.yml,_config.local.yml`.

## Writing content
- Create posts in `_posts/YYYY-MM-DD-title.md` with front matter (`title`, `layout: single`, `author_profile: true`, etc.).
- Add or update pages in `_pages/`; wire them into navigation via `_data/navigation.yml` if needed.
- Homepage copy lives in `index.md`.

## Publishing
Commits to the default branch trigger a GitHub Pages build using the `github-pages` gem and Minimal Mistakes. For a production preview, run:
```bash
bundle exec jekyll build
```
Inspect `_site/` locally before pushing.
