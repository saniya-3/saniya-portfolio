# Personal Portfolio (Bootstrap)

A small, hand-written portfolio that looks clean and is easy to extend. No build tools, just HTML/CSS/JS + Bootstrap CDN.

## Quick Start (GitHub Pages)
1. Create a repo named `username.github.io` (or any repo and enable Pages).
2. Upload everything in this folder to the repo root.
3. Commit and push. For non-root repos, enable **Settings → Pages → Deploy from branch**.
4. Done. Visit your Pages URL.

## Customize
- `index.html`: Search for **TODO** and update your name, email, links.
- `assets/img/profile.svg`: swap with your photo (keep the same filename or update the `<img>` src).
- `assets/Saniya-Resume.pdf`: replace with your resume (or remove the button).
- Project cards: update titles, descriptions, and the `Live/Code` links.

## Contact form
Uses a simple `mailto:` action (works fine for Pages). If you prefer a form service later, replace the `action` attribute with your provider (e.g., Formspree).

## Notes
- Keep images lightweight. The sample artwork are SVGs for speed.
- Accessibility: keyboard focus styles are enabled and color contrast is Bootstrap-defaults.
