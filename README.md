# Master Chef Academy

A lightweight personal culinary training site. It is intentionally static: no login, backend, database, package installation, or build process.

## Features

- Responsive navy, gold, white, and light-grey interface
- Two complete cooking lessons
- Serving scaling from 2–12 portions
- US-volume and ingredient-density metric conversions
- Shopping lists, mise en place, timelines, detailed instructions, troubleshooting, plating, skills, scoring, and Kitchen Mode
- Browser-local kitchen journal
- Print-friendly lesson pages

## Run locally

Open `index.html` directly, or serve the directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

Import this repository into Vercel. Vercel should identify it as a static site. No build command is required and the output directory is the repository root (`.`).

## Project structure

- `index.html` — site shell
- `styles.css` — responsive visual design
- `app.js` — lesson data, scaling, conversions, Kitchen Mode, and journal behavior
- `vercel.json` — static deployment settings and basic headers
