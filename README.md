# Aditi Singh — Portfolio

A single-page, editorial portfolio for **Aditi Singh** — MBA graduate, AI-fluent
operations & project management professional based in Berlin.

Black-and-white editorial aesthetic with a champagne-gold accent. Built as one
self-contained `index.html` (HTML + CSS + vanilla JS). No build step, no
frameworks — just open it or drop it on any static host (Netlify, GitHub Pages, etc.).

## Features
- Full-bleed hero with line-by-line headline reveal and a portrait frame
- Scroll-triggered fade/slide animations (`IntersectionObserver`)
- Animated counters in the dark "Impact" section
- Expandable experience timeline
- Hover-reveal project cards with tech stacks
- Animated language proficiency bars
- Optional dark-mode toggle
- Fully responsive (mobile-first), with a hamburger menu on small screens
- Google Fonts (Playfair Display + Plus Jakarta Sans); no other dependencies
- SEO/meta + Open Graph tags

## Things to swap in
1. **Headshot** — replace the placeholder file `aditi-hero.jpg` (referenced in the
   hero `<img>`). A portrait crop around 4:5 works best.
2. **CV download** — the *Download CV* button links to `#`. Point its `href`
   (the `#cvBtn` anchor in the hero) at the real CV file or link.

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
