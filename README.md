# STAR Creative Agency — Government Landing Page

A single-page, self-contained landing page for **STAR Creative Agency LLC**, targeting government departments and public-sector procurement offices.

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The complete landing page (inline CSS/JS, no build step, no external JS dependencies). |
| `assets/STAR-Creative-Agency-Capability-Statement.pdf` | Downloadable capability statement linked from the hero and contact sections. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (skips Jekyll processing). |

## Highlights

- **Audience-tuned copy** — framed for contracting officers: capabilities, past performance, differentiators, and a procurement quick-reference (UEI, NAICS, certifications).
- **Accessible by design** — semantic landmarks, skip link, labeled nav, keyboard focus styles, and reduced-motion support (demonstrates the WCAG/ADA competency the statement claims).
- **Responsive** — mobile nav, fluid type, and reflowing grids down to small screens.
- **Government look & feel** — Public Sans + Merriweather pairing (the U.S. Web Design System fonts) with a civic navy/gold palette and STAR motif.

## Publishing on GitHub Pages

1. Push to the `main` branch.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. The site publishes at `https://starlyns.github.io/star_government/`.

To serve it on a custom domain (e.g. `gov.starlyns.com`), add a `CNAME` file with that hostname and configure DNS.

## Editing content

All copy and company data live directly in `index.html`. The only external requests are the Google Fonts stylesheet; everything else (styles, scripts, icons, favicon) is inline, so the page works offline and loads fast.
