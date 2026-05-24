# Goa Trip Itinerary

A simple, travel-themed static page for a 2-day Goa trip, built as a single HTML file and styled for a polished, mobile-friendly presentation.

## What’s in this repo

- `goa.html` — the complete itinerary page with the day-by-day plan, maps, travel notes, and a monsoon advisory
- `README.md` — project overview and usage notes

## Trip highlights

### Day 1
- Dudhsagar Falls
- Spice plantation brunch
- Fort Aguada
- Dinner at Souza Lobo
- Nightcap at Thalassa

### Day 2
- Baga Beach water sports
- Lunch at Britto’s
- Chapora River mangrove kayaking
- Farewell sunset dinner at La Plage
- Departure from Vasco da Gama

## How to view

Open `goa.html` in any modern browser.

If you are using a local server, you can also run:

```bash
python3 -m http.server
```

Then open `http://localhost:8000/goa.html`.

## Notes

- The page includes embedded Google Maps links for each stop.
- The design uses inline CSS and a small IntersectionObserver script for subtle animations.
- The content is tailored to the June 12–13, 2026 trip plan.

## Deploy on Netlify

This site is a static HTML page, so deployment is straightforward.

1. Push this repository to GitHub (or connect it directly to Netlify).
2. In Netlify, choose **Add new site** → **Import an existing project**.
3. Set:
   - **Build command:** leave empty
   - **Publish directory:** `.`
4. Deploy.

A `netlify.toml` file is included so the site redirects to `goa.html` at the root URL.

## Project status

This repository is intentionally lightweight and static. It is ready to be shared, hosted, or adapted for another trip itinerary.
