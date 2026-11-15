# Bravovic

Viktor's link-in-bio landing page. One goal: get a visitor to text their problem in an Instagram DM.

Static HTML/CSS/JS, no build step, no dependencies. Everything is in `index.html`; images are in `assets/`.

## The page

Four screens over a fixed starfield canvas that streams outward as the page scrolls:

1. **Hero** — portrait and logo, headline, call to action.
2. **Work** — three client projects, each linking to the live site.
3. **Plans** — free practical plans by email. The form posts to the URL in `PLANS_ENDPOINT` (in `index.html`); while that is empty, nothing is sent.
4. **Finale** — the ask, with the Instagram DM button.

The page never takes over scrolling: no pinned sections, no held gestures.

## Local development

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
npx serve .
```

## Deployment

Deployed to Vercel from this repository's `main` branch: https://bravovic.vercel.app

The share image (`assets/share.jpg`) is referenced by its full URL in the `og:image` tag. If the site moves to another domain, update that tag and `og:url`.
