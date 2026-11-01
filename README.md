# K-POP SCHEDULE HUB

K-POP SCHEDULE HUB is a responsive, browser-based planner for K-pop fans. Users can manage favorite artists, track events, view a monthly calendar, and follow a live countdown to the next scheduled event.

## Main features

- Dashboard with upcoming events, event totals, favorite artist count, and countdown timer
- Favorite artist management with artist name and fandom name
- Add, edit, filter, and delete event entries
- Event categories for comebacks, concerts, fan meetings, and music shows
- Monthly calendar with highlighted event dates
- LocalStorage persistence across browser refreshes
- Responsive lavender, purple, pink, and white interface for desktop and mobile
- Static deployment compatible with GitHub Pages

## Technologies used

- HTML5
- CSS3
- Vanilla JavaScript
- Browser LocalStorage
- Google Fonts loaded through the stylesheet link in `index.html`

No backend, build step, package manager, or paid API is required for the current version.

## Installation

1. Download or clone this project.
2. Open the project folder in a code editor.
3. No dependency installation is required.

## Local execution

The simplest option is to open `index.html` directly in a modern browser.

For a local static server, run one of the following from the project folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## GitHub Pages

Upload `index.html`, `styles.css`, and `app.js` to the selected GitHub Pages branch or directory. Because the project uses relative file paths and has no build step, GitHub Pages can serve it as a static website.

The `upload` folder contains the deployment-ready files prepared for upload.

## Data and privacy

User-created artists and events are saved only in the browser's LocalStorage. The project does not contain API keys, passwords, or server credentials.
