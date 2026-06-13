# DateDice 🎲❤️

A date-night randomizer for the SF Bay Area. Pick a region, set how far you want to roam, and let the dice plan the night — breakfast, dinner, drinks, a hike, a scenic drive, or a night in.

Currently scoped to **North Marin** and **South Marin**, with more regions on the way.

**Live demo:** _(add your Netlify / GitHub Pages URL here once deployed)_

## Features

- Tap-the-dice launch with a cream + black dice pair (centered heart faces)
- Per-region category grid: Breakfast, Cozy, Adventure, Lunch, Home, Dinner, Drinks, Drive, Dessert, Demons
- One-tap **"Roll the Dice"** to plan the whole night at once
- A **distance dial (1–10 mi)** anchored to Black Point, Novato — every spot shows how far it is, and the dial filters results
- **Menu**, Yelp, Google reviews and Maps links on every food spot; Maps + TripAdvisor on every place
- Re-roll button on every result
- Light theme, dark theme, and an after-dark "Demons" sub-theme
- Minimal map-style line icons throughout — no emoji
- Single self-contained file, no build step, no dependencies (fonts load from Google Fonts)

## Run it

It's one HTML file. Just open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

### Netlify (drag & drop)
1. Go to https://app.netlify.com → **Add new site** → **Deploy manually**
2. Drag the whole project folder (or just `index.html`) onto the drop zone.

### Netlify (from this repo)
Connect the repo in Netlify — `netlify.toml` is already configured to publish the root.

### GitHub Pages
Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**, pick `main` / root. Your site appears at `https://<username>.github.io/<repo>/`.

## A note on the data

Venue listings are hand-curated from local knowledge, not a live feed. Always tap through to Maps or Yelp to confirm hours before you head out.

## License

MIT — see [LICENSE](LICENSE).
