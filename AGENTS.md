# AGENTS.md — shabbirAlam.github.io

## What this is

A single-page static portfolio site deployed on **GitHub Pages** (user site). No build tools, no frameworks, no dependencies — just `index.html` + `styles.css` + inline JS.

## Deployment

- Push to `main` → auto-deploys to `https://shabbirAlam.github.io`.
- No build/CI step. `index.html` is served directly from the repo root.
- GitHub Pages user site: the repo name must match `<username>.github.io`.

## Development workflow

1. Edit `index.html` or `styles.css`.
2. Open `index.html` directly in a browser to preview (no dev server needed).
3. Commit and push to `main`.

No `npm`, `yarn`, `package.json`, test runner, linter, or formatter exists.

## Quick commands

```bash
# Preview locally
open index.html

# Deploy
git add index.html styles.css && git commit -m "..." && git push
```

## Structure

```
index.html   # HTML + inline JS (scroll-reveal, mobile nav toggle)
styles.css   # all styles (dark theme, responsive, animations)
README.md    # placeholder
AGENTS.md    # this file
```

## Notes

- Using Font Awesome 6.5.0 via CDN for icons.
- Dark theme with CSS custom properties (`--bg-primary`, `--accent`, etc.) — all theming lives in `:root` in `styles.css`.
- Scroll-triggered reveal animations via `IntersectionObserver` (inline `<script>` at bottom of `index.html`).
- Mobile nav uses inline `onclick` toggle + event listener for link close.
- WhatsApp contact number: +91 9038474524 (hardcoded in hero buttons, contact section, and floating button).
- Contact email: `mdshabbiralam007@gmail.com`.
- All content (hero, about, skills, experience timeline, education, contact) is in the single HTML file.
