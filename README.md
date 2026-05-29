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
- Dedicated Volunteering section (Imagine Foundation career coaching)
- Optional dark-mode toggle
- Fully responsive (mobile-first), with a hamburger menu on small screens
- Three-font system via Google Fonts, each with a role: Playfair Display
  (display headings), Plus Jakarta Sans (body), Space Grotesk (labels/metadata);
  no other dependencies
- SEO/meta + Open Graph tags

## Assets in the repo
- **Headshot** — `aditi-hero.png` (800×800), shown as a circular portrait in the hero.
  To change it, replace the file (keep the name, or update the `<img src>` and the
  `og:image` meta tag).
- **CV** — `Aditi_Singh_General_CV.docx`, linked from the *Download CV* button.
  Swap the file (or point the `#cvBtn` anchor elsewhere) to update it.

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
