# Travel Advisor Site

A static site based on a Stitch-generated "VoyageCurator" template, used here as a starting point for a personalized travel advisory site.

## Structure

- `index.html` — Home
- `services.html` — Our Services
- `about.html` — About Us
- `contact.html` — Contact Us
- `DESIGN.md` — design system reference (colors, type scale, spacing) from the original template

Styling is done with the Tailwind CDN build (loaded per-page via `<script src="https://cdn.tailwindcss.com">`) plus an inline Tailwind config in each page's `<head>`. Hero and section images are currently placeholder URLs hosted on Google's `lh3.googleusercontent.com` — swap these for your own images before launch.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploying

This repo is set up for GitHub Pages. In the repo's Settings → Pages, set Source to "Deploy from branch", branch `main`, folder `/ (root)`.

## Known limitations

- The contact form (`contact.html`) has no backend — the submit button is a no-op. Wire it up to a form service (e.g. Formspree) or your own backend before relying on it.
- Footer links (Newsletter, Privacy Policy, Terms of Service, FAQ) are placeholders (`#`).
