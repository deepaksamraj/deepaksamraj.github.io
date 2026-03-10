# deepaksam.github.io

> Personal resume website — built as a single-file, zero-dependency HTML/CSS/JS page.

Live at **[deepaksam.github.io](https://deepaksam.github.io)**

---

## Why single-file?

No build pipeline, no node_modules, no framework overhead.  
The entire site — animations, tag filtering, scroll reveal, SVG cert badges — ships as one `index.html`.  
Loads fast. Easy to maintain. Deployable anywhere.

## Features

- **Tag-filter system** — multi-select experience bullets by skill area with smooth collapse animation
- **Vertical year timeline** — career history mapped against a proportional year axis
- **Cert badge strip** — real company logos via Clearbit API with SVG fallbacks
- **Scroll reveal** — intersection observer animations, gracefully degraded
- **Cursor glow** — subtle radial gradient that follows the pointer
- **Dark theme** — custom design system with CSS variables, no Tailwind or Bootstrap

## Stack

| Layer | Choice |
|---|---|
| Markup | Semantic HTML5 |
| Styling | Vanilla CSS with custom properties |
| Scripting | Vanilla JS — event delegation, IntersectionObserver |
| Fonts | Plus Jakarta Sans · IBM Plex Mono · IBM Plex Serif (Google Fonts) |
| Logos | Clearbit Logo API |
| Hosting | GitHub Pages |

## Use as a template

Feel free to fork and adapt for your own resume.  
All content lives in `index.html` — sections are marked with comments like `<!-- EXPERIENCE -->`, `<!-- CERTIFICATIONS -->` etc.  
No install step. Just edit and push.

---

*"walking by faith, scaling by design" — Ephesians 3:20*