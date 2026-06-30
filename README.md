# Movies Search Web App
A responsive client-side movie discovery interface that uses The Movie Database (TMDB) API to display popular films, search titles, and surface ratings with overview overlays.

## Features
- Browse popular movies from TMDB on page load
- Search movies by title using the TMDB search endpoint
- Display movie posters, titles, rating, and overview overlay
- Client-side pagination with prev/next controls and page buttons
- Hover-activated search input interaction
- Responsive card-based UI with dark theme styling

## Tech Stack
- HTML5
- CSS3
- JavaScript (ES modules)
- TMDB API
- Font Awesome CDN for icons

## Installation
1. Clone or download the repository.
2. Open the project folder in your browser.
3. Open `index.html` directly, or serve the folder with a local HTTP server for best results.

### Example local server
```bash
# Python 3
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## API Routes / Endpoints
The app consumes TMDB endpoints directly from the browser:
- Popular movies: `https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=<API_KEY>&page=<page>`
- Search movies: `https://api.themoviedb.org/3/search/movie?api_key=<API_KEY>&query=<searchTerm>`

## Usage
1. Open `index.html` in a browser.
2. Hover over the search icon to expand the search input.
3. Enter a movie title and press the search button.
4. Browse results and click pagination buttons to navigate pages.
5. Hover over a movie card to read the movie overview.

## Folder Structure
- `index.html` — main application HTML shell
- `style.css` — layout, colors, responsive card styles
- `script.js` — TMDB API integration, search logic, pagination, DOM rendering
- `Images/` — static image assets used by the site
- `README.md` — project documentation

## Notes
- The interface is purely client-side and does not include a backend.
- The app currently displays search results and movie details but does not stream or play movies.

## Author
**Muhammad Muzammil** (Monarch of Code) — Full Stack Developer

