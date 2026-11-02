# AGENTS.md

## Architecture
This is a static site with no framework, no package.json and no build step. Netlify publishes the repository root as-is (see `netlify.toml`).

## Files
- `index.html`: the entire landing page (nav, hero with terminal mock, features grid, quickstart, footer). A small inline script handles the footer year and the "Copy" button.
- `styles.css`: all styles. Theme tokens are CSS variables in `:root`.
- `netlify.toml`: sets `publish = "."`.

## Conventions
- Keep it dependency-free. Don't add a bundler or framework unless explicitly requested.
- Reuse the existing CSS variables instead of hard-coding colors.
- Respect `prefers-reduced-motion`. Animations are disabled there.
- GitHub links currently point to `https://github.com/` as placeholders for the owner's repository URL.
