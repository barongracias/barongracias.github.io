# barongracias.github.io

Source for my personal site/portfolio built with Jekyll and the Minimal Mistakes remote theme. Posts and pages live in Markdown; GitHub Pages builds and hosts the site.

## Structure
- `_config.yml` — site metadata, theme options, plugins.
- `_pages/` — standalone pages (about, projects, etc.).
- `_posts/` — dated blog posts with front matter.
- `_data/` — navigation, authors, and other YAML-driven settings.
- `assets/` and `files/` — images, downloads, and other static content.
- `_site/` — generated output for local builds (GitHub Pages will rebuild from source).

## Run locally
Prerequisites: Ruby + Bundler.
```bash
bundle install
bundle exec jekyll serve --livereload
# open http://localhost:4000
```
Stop and restart the server after changing `_config.yml` or installing new gems.

## Writing content
- Create posts in `_posts/YYYY-MM-DD-title.md` with front matter (title, categories/tags, `layout: single`, `author_profile: true`).
- Add or update pages in `_pages/`; include them in navigation via `_data/navigation.yml` if needed.
- Home copy lives in `index.md` (uses the theme’s `single` layout with the author profile).

## Publishing
Commits to the default branch trigger a GitHub Pages build using the `github-pages` gem and Minimal Mistakes. For a production preview, run `bundle exec jekyll build` and inspect `_site/` locally.
