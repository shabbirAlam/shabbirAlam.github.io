# AGENTS.md - shabbirAlam.github.io

## Scope

This file contains instructions for AI coding agents working on this static GitHub Pages portfolio. For the project overview and repository layout, see [README.md](README.md).

## Project constraints

- There is no build step, framework, package manager, test runner, linter, or formatter.
- The site is served directly from the repository root.
- External Google Fonts and Font Awesome 6.5.0 CDN assets require network access in the browser.

## Editing rules

- Edit `index.html` for page content, links, navigation, and inline JavaScript.
- Edit `styles.css` for theme, layout, responsive rules, and animations.
- Preserve the relative path and filename casing of `resources/profile-picture.jpg`.
- Resume links start as `#resume` placeholders and are assigned a Google Drive URL by inline JavaScript.
- Preserve the hamburger menu's `.open` class behavior and the `IntersectionObserver` scroll-reveal behavior when changing related markup or scripts.
- Preserve accessible image alt text and `rel="noopener"` on external links.

## Validation

1. Open `index.html` directly in a browser with `open index.html`.
2. Check desktop and narrow/mobile layouts.
3. Verify navigation anchors, image loading, resume, email, phone, social, and WhatsApp links.

## Deployment

When GitHub Pages is configured to publish from `main`, pushing changes deploys the site automatically. Keep the repository name as `<username>.github.io` for a user site.

Do not commit or push unless explicitly requested. Do not add build tooling or dependencies unless the project requirements change.
