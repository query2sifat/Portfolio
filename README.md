# Portfolio — Md Sifat Alam Tonmoy

A single-page, dark-themed personal portfolio built with plain HTML/CSS/JS — no build step, no dependencies to install. Live at **[query2sifat.github.io/Portfolio](https://query2sifat.github.io/Portfolio/)**.

## Features

- **Hero** — animated canvas background (drifting particles + layered waves), availability status badge
- **About** — profile summary and core competencies
- **Projects** — featured project cards *(placeholder content — replace with your own work)*
- **Interests** — areas of focus
- **Certifications** — 15 verified credentials with a category filter (All / Google / University / Languages)
- **Hire banner** — social links and direct email contact
- Responsive layout with a mobile hamburger menu

## Tech stack

- HTML5 + CSS3 (custom properties, no framework)
- Vanilla JavaScript (canvas animation, certificate filtering, mobile nav)
- [Font Awesome](https://fontawesome.com/) for icons
- [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) via Google Fonts

## Project structure

```
.
├── index.html              # Entire site (markup, styles, and scripts)
├── .github/workflows/
│   └── static.yml           # GitHub Actions workflow — deploys to GitHub Pages on push to main
├── LICENSE                  # Apache-2.0
└── README.md
```

## Running locally

No build tools required — just open the file:

```bash
git clone https://github.com/query2sifat/Portfolio.git
cd Portfolio
open index.html   # or double-click it / use a local server like `npx serve`
```

## Deployment

Pushing to `main` automatically deploys to GitHub Pages via the workflow in `.github/workflows/static.yml`. To enable it on a fork, turn on **Pages → Source: GitHub Actions** in the repo settings.

## Customizing

- **Projects**: swap the placeholder cards in the `#projects` section with your real work and links.
- **Social links**: update the `#` placeholders in the hire banner with your actual GitHub, LinkedIn, Kaggle, and Facebook URLs.
- **Certifications**: duplicate a `.cert-card` block and update the issuer, title, date, and verification link.

## License

Apache-2.0 — see [LICENSE](./LICENSE).
