# Launchpad

A simple, single-page landing page for an open-source project. It's plain HTML and CSS with no build step, so it deploys straight from this Git repository on Netlify.

## Technologies

- HTML5 and CSS (`index.html`, `styles.css`)
- Google Fonts (Space Grotesk, JetBrains Mono)
- Netlify for hosting. `netlify.toml` publishes the repo root.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or, with Netlify emulation:
netlify dev
```

## Customize

- Change the copy and links in `index.html`. Replace the `https://github.com/` placeholders with your repository URL.
- Change the brand colors through the CSS variables at the top of `styles.css`, especially `--accent`.

## Deploy

Push to `main`. Netlify deploys every commit automatically.
