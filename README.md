# Plot Twist

A colorful, minimalist movie chooser for the end of a long day.

## How it works

1. Start on the landing screen.
2. Choose a genre and runtime in two simple preference questions.
3. Play a short card-matching game to reveal a movie that fits.

The app includes 30 curated movies, responsive layouts, keyboard-accessible controls, and links to movie details on IMDb. It does not require an API key or backend. Streaming availability is not tracked.

## Run locally

Requires Python 3:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173 in your browser.

## Project files

- `index.html`: page shell and metadata
- `style.css`: responsive styling
- `app.js`: preferences, curated catalog, and matching game
- `hero.png`: original AI-generated illustration

Built with HTML, CSS, and JavaScript. Fonts load from Google Fonts, with local fallback fonts available.
