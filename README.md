# UTSP startup site

Static GitHub Pages site for the Urban Transportation Synchronization Platform.

UTSP is a commuter-powered mobility intelligence concept. It turns reports about
traffic, accidents, potholes, and unmarked speedbreakers into a shared picture
of what is happening across a city.

## How it works

1. A commuter observes a delay or road condition.
2. The mobile product captures evidence, location, and place context.
3. Reports appear in a shared map and activity feed.
4. Communities and mobility teams use the signal to make better decisions.

## Site structure

- `index.html` contains the product story, platform sections, roadmap, and pilot CTA.
- `styles.css` contains the responsive visual system and mobile layout.
- `script.js` powers the mobile menu, scroll reveals, and map signal filters.
- `README.md` contains project and publishing notes.

## Run locally

Open `index.html` directly, or serve the folder with any static web server:

```bash
python -m http.server 8000
```

The site has no build step or runtime dependencies, so it can be published directly from a GitHub repository.

After starting the local server, open `http://localhost:8000` in a browser.