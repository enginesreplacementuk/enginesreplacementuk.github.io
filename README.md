# enginesreplacementuk.github.io

A static informational page about **replacement engines UK**, built for GitHub Pages. The site explains how to diagnose engine failure, choose between new, reconditioned, and used replacement engines, understand UK pricing, and source a unit safely — with a link out to a specialist sourcing partner.

## Files

| File | Purpose |
|---|---|
| `index.html` | The full page: design, structured content (2000+ words), semantic HTML, JSON-LD (Article + FAQPage), no buttons. |
| `robots.txt` | Allows all crawlers and points to a sitemap. |
| `README.md` | This file. |

## Design notes

- **Display type:** Oswald (condensed, stamped-plate headings)
- **Body type:** Source Serif 4 (readable, editorial)
- **Utility type:** IBM Plex Mono (spec data, FAQ labels)
- **Signature element:** an "engine ID plate" component (riveted, stamped-metal styling) used for spec callouts, the partner mention, and the FAQ — a nod to real engine identification plates.
- **No interactive buttons** anywhere in the layout — navigation and the partner mention use plain text links only.

## Publishing on GitHub Pages

1. Push these files to the root of the `enginesreplacementuk/enginesreplacementuk.github.io` repository (the repo name must exactly match the domain for the default GitHub Pages user-site setup).
2. In **Settings → Pages**, set the source branch to `main` and the folder to `/ (root)`.
3. The site will be live at `https://enginesreplacementuk.github.io/` within a few minutes.

## Editing content

All visible text lives inside `index.html` between the `<article>` tags. Each topic is its own `<section>` with an `id`, so you can jump to and edit any part (failure signs, engine types, costs, warranty, FAQ, etc.) independently without breaking the layout.
