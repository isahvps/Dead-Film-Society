# THE FILM ARCHIVE

A personal digital cinematheque built with vanilla HTML, CSS and JavaScript.

## Run locally

Open `index.html` in a modern browser. No build step or API key is required for the demo.

## Included

- Overview dashboard and collection stats
- Directors' Archive
- Horror Archive with subgenre filters
- Suspense & Mystery section
- Interactive Film Roulette with collection filters
- Sci-Fi & Fantasy section
- Watchlist with search, sorting and custom film entries
- Film Diary with ratings and notes
- LocalStorage persistence
- JSON archive export
- Responsive layout for desktop and mobile

## Publish on GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and optionally this README.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish your site.

## Notes

- Demo collection data is built into `script.js`.
- Personal changes are stored in this browser's LocalStorage. They do not sync between devices.
- The TMDB API is not connected in this first demo build. The site works without an API key.
- Poster images load from TMDB image hosting when available; missing images fall back to designed poster placeholders.
