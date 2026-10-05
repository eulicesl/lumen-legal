# Lumen — Legal & Privacy

This repository hosts the publicly-reachable privacy policy and terms of use for **Lumen**, a privacy-first AI assistant for iPhone and iPad.

GitHub Pages publishes the site from the `main` branch, site root `/`. After a merge to `main`, Pages rebuilds automatically (usually within a minute).

## Live URLs

| Page | File | Live URL |
|---|---|---|
| Privacy Policy | `index.html` | https://eulicesl.github.io/lumen-legal/ |
| Terms of Use | `terms/index.html` | https://eulicesl.github.io/lumen-legal/terms/ |

The Privacy URL is linked from the App Store listing and the app's Settings screen. The Terms URL is linked from the in-app paywall (App Store Guideline 3.1.2). A folder named `terms/` containing `index.html` is the standard GitHub Pages path for `/terms/`.

## What's here

- `index.html` — Privacy Policy, served as the site's root page.
- `terms/index.html` — Terms of Use, served at `/terms/`.

Each page is a standalone HTML file (same CSS, light/dark via `prefers-color-scheme`).

## Updating these pages

1. Edit `index.html` and/or `terms/index.html` directly.
2. Update the `Last updated` date near the top of any page you change.
3. Keep the two pages cross-linked (Privacy ↔ Terms).
4. Commit and push to `main` (or merge a PR targeting `main`).
5. GitHub Pages rebuilds from `main` automatically. Confirm:
   - https://eulicesl.github.io/lumen-legal/
   - https://eulicesl.github.io/lumen-legal/terms/

## License

Content in this repo is released under CC BY 4.0 so anyone can reuse or adapt these pages as a starting point for their own apps.
