# Project Structure

```
.
├── _config.yml          # Jekyll configuration (title, plugins, timezone)
├── _layouts/
│   └── base.html        # Root HTML layout (doctype, body wrapper)
├── _includes/
│   └── head.html        # <head> partial (meta, favicon, CSS links)
├── assets/
│   └── css/
│       └── main.css     # All styles (reset + custom, single file)
├── index.html           # Homepage (profile + social links)
├── 404.html             # Custom 404 page
├── Gemfile              # Ruby dependencies
├── Makefile             # Dev shortcuts (install, dev server)
├── .editorconfig        # Editor formatting rules
├── .github/
│   └── workflows/
│       └── jekyll-gh-pages.yml  # CI/CD deploy pipeline
├── favicon-16x16.png
├── favicon-32x32.png
└── favicon.ico
```

## Key Patterns

- **Layouts:** Single `base.html` layout wraps all pages
- **Includes:** `head.html` is the only partial; contains meta tags, favicons, and stylesheet links
- **Styling:** One flat CSS file with a normalize/reset section followed by custom styles
- **Pages:** Use YAML front matter with `layout: base`
- **No JavaScript** — the site is purely static HTML + CSS
