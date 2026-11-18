# Arian Aghamohseni — personal website

Static portfolio published at https://arianaghamohseni.github.io/.

## Preview locally

```sh
python3 -m http.server 8088
```

Open http://localhost:8088/. No package installation or build step is required.

## Update

- `index.html`: biography, research, manuscripts, education, and contact links.
- `styles.css`: responsive layout, typography, print styles, and reduced motion.
- `script.js`: accessible mobile navigation. Page content also works without JS.
- `assets/`: favicon and social preview image.
- `sitemap.xml`: update `lastmod` when publishing a substantive revision.

Research entries and manuscript statuses were retained from the prior portfolio.
Confirm new affiliations, publication decisions, author lists, and results with
Arian before changing these claims. Entries with only a start date do not assert
an ongoing institutional appointment.

GitHub Pages publishes the repository root through `.github/workflows/pages.yml`
on pushes to `main`. Do not put tokens, environment files,
internal project documents, or private service endpoints in this repository.
