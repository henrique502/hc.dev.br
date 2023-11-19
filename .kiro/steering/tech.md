# Tech Stack

## Core

- **Static site generator:** Jekyll
- **Language:** HTML with Liquid templating
- **Styling:** Plain CSS (no preprocessor, no framework)
- **Icons:** LineIcons 4.0 (CDN)
- **Ruby gems:** jekyll, jekyll-sitemap, webrick, tzinfo-data

## Hosting & Deployment

- GitHub Pages with automated deployment via GitHub Actions
- Workflow: `.github/workflows/jekyll-gh-pages.yml`
- Deploys on push to `main` branch

## Common Commands

```bash
# Install dependencies
make install
# or: bundle install --path vendor/bundle

# Run local dev server with live reload
make dev
# or: bundle exec jekyll serve --watch
```

## Conventions

- Indent: 2 spaces (all files)
- Line endings: LF
- Charset: UTF-8
- Final newline: always
- Trailing whitespace: trimmed (except .md files)
