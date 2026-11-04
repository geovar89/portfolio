# George Varvates — Refactored Portfolio

A responsive, accessible, dependency-light personal portfolio for product leadership, AI, digital mobility and FinTech.

## Structure

```text
index.html                  Semantic content, metadata, inline product framework SVG
assets/css/styles.css       Layout, components, responsive rules, print styles
assets/js/main.js           Accessible mobile navigation and dynamic copyright year
assets/images/favicon.svg  Local SVG favicon
```

## Local preview

Open `index.html` in a browser. Alternatively, from this directory:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Publish

Static hosting: upload the *contents* of this folder to GitHub Pages, Azure Static Web Apps, Netlify or any static web host. No build step or Node dependency is required.

## Maintenance

- Update copy and case studies in `index.html`.
- Adjust design tokens in `assets/css/styles.css` under `:root`.
- Update the early AI assistant metrics when fresh reporting is available.
- Replace the initial status of Skip the Counter if the initiative's actual stage changes.
- Add a canonical URL and social preview image once a public domain is selected.
- Do not describe the current role as having direct reports or sole roadmap ownership; current prioritization is shared with IT.

## Design / accessibility

- Semantic sections and heading hierarchy.
- Working internal anchors and mobile nav toggle with ARIA.
- Focus-visible states, skip link, contrast-aware buttons and reduced-motion preference.
- Responsive layouts and a vector Hero framework to prevent text clipping.
- No UI framework, no tracked scripts, no external imagery (optional Google Fonts has fallbacks).

## Content policy for this portfolio

The figures `435`, `87%`, and `93%` refer to an early AI assistant reporting sample and are labeled as such. Skip the Counter is presented as a POC/initiative, not as a launched product. These descriptions should be reviewed before publishing public project details.
