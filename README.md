# Bravovic

A single-page landing site: a black starfield hero with a hidden "WHY NOT ME NOW" constellation that reveals itself as you scroll, a horizontal scroll-jacked project gallery, and a logo that expands from `B\C` to the full wordmark.

Static HTML/CSS/JS, no build step, no dependencies — just `index.html`.

## Status

This is a first structural pass, not final content:
- Copy, headline and subheadline text are placeholders.
- The "My websites" gallery cards are placeholders — swap in real projects, images and links.
- The CTA buttons ("Ask why", "Why not?", "Start now") don't go anywhere yet — wire them to a real destination (contact form, mailto, booking link, etc.).
- No navigation menu, footer legal pages (Privacy/Terms), or SEO meta tags (description, Open Graph, favicon) yet.

## Local development

No build step needed — open `index.html` directly in a browser, or serve it with any static server:

```bash
npx serve .
```

## Deployment

Deployed to Vercel from this repository's `main` branch.
