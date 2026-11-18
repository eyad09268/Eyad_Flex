<div align="center">

# Eyad Flex

**A sleek, glassmorphic cinema discovery and streaming web app powered by TMDB and VidSrc.**

[![HTML5](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![TMDB API](https://img.shields.io/badge/Data-TMDB%20API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white)](https://www.themoviedb.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

</div>

---

## Features

- **Glassform UI** — Frosted glass header, floating navigation pill, translucent media cards, specular highlights, and ambient background gradients.
- **Live TMDB Catalog** — Real-time trending hero slider, Top 10 rankings, and curated rows for movies, series, action, comedy, drama, and new releases with a 10-minute in-memory cache.
- **Browse by Provider** — 16 custom vector streaming service icons (Netflix, Prime Video, Disney+, Apple TV+, Hulu, HBO Max, Paramount+, Peacock, Crunchyroll, and more) that filter movies by provider.
- **Integrated Playback** — Built-in VidSrc.to theater player modal with YouTube trailer support and quick episode switching for TV series.
- **Instant Multi-Search** — Debounced live search across movies and TV shows with keyboard navigation (`Esc` to close modals).
- **My List** — Persistent watchlist saved locally in `localStorage`.

---

## Quick Start

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/eyad-flex.git
   cd eyad-flex
   ```
2. Open `index.html` directly in any modern browser, or serve it locally:
   ```bash
   python3 -m http.server 8080
   ```
3. Visit `http://localhost:8080`.

---

## Deploy with GitHub Pages

1. Go to your repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select `main` and `/ (root)`, then click **Save**.
4. Your site will be live at `https://<your-username>.github.io/eyad-flex/`.

---

## Project Structure

```text
eyad-flex/
├── index.html   # Self-contained single-file web application
├── README.md    # Project documentation
└── LICENSE      # MIT License
```

---

## Disclaimer

Eyad Flex does not host any video files on its servers. All streams are provided by non-affiliated third parties, and catalog metadata/artwork are powered by [TMDB](https://www.themoviedb.org/).
