# Meta Tag Analyzer

A free, client-side Meta Tag Analyzer tool. Paste any URL or raw HTML and get a full audit of the page's meta tags — title, description, Open Graph tags, Twitter cards, canonical links, robots directives, and more. Everything runs in the browser; no server, no login, no data leaves your device.

## Features

- **Full meta-tag audit**: extracts and displays all `<meta>` tags from a page or pasted HTML
- **SEO checks**: title length, meta description length, missing/invalid tags flagged
- **Open Graph preview**: see how the page looks when shared on Facebook/LinkedIn
- **Twitter card preview**: check `twitter:card` rendering details
- **Canonical & robots**: validates canonical URL and robots directives
- **Copy-ready report**: copy the analysis results to your clipboard
- **100% client-side**: single HTML file, zero dependencies, works offline after load

## Tech Stack

- Plain HTML5, CSS, and vanilla JavaScript
- No build step, no frameworks, no backend
- Deployed as a static site on GitHub Pages

## Project Structure

```
.
├── meta-tag-analyzer.html   # original tool file
├── index.html               # same tool, entry point for GitHub Pages
├── README.md
└── LICENSE
```

## Quick Start

Just open `index.html` (or `meta-tag-analyzer.html`) in any modern browser — no install, no build:

```bash
# Option 1: open the file directly
xdg-open index.html   # or just double-click it

# Option 2: serve locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy Notes

This is a purely static, dependency-free site. It is deployed via **GitHub Pages** directly from the `main` branch root. Any change pushed to `main` is live after the next Pages build. No secrets or environment variables required.

## License

See [LICENSE](./LICENSE).

---

Built by [Girish Lade](https://ladestack.in) — see more projects at [ladestack.in](https://ladestack.in).
