# CyberTab

A futuristic new-tab page with a neon-black aesthetic — fast, minimal, and deeply customizable.

CyberTab gives your browser a moody, retro-futuristic new-tab experience with three core features you'll love:

- Bookmarks section: quick access to your most-used sites with large neon tiles.
- Search engine changer: pick or add the search engine you want and search right from the bar.
- Neon black vibe: dark background with high-contrast neon accents for a sleek, cyberpunk look.

---

## Features

- Clean, responsive new-tab layout optimized for both wide and narrow screens.
- Bookmarks panel with visual tiles, drag-and-drop reordering, and optional folder grouping.
- Search bar with a selectable search engine dropdown — switch between engines instantly.
- Theme built around a neon-on-black color palette, with simple CSS variables so you can tweak colors and glow intensity.
- Lightweight and privacy-minded: no trackers and no external analytics by default.

---

## Demo

Open a new tab (or load the extension) to see the neon-black UI. The main view shows a centered search bar, a grid of bookmarks below it, and a small settings icon for customization.

(Replace this with screenshots or GIFs in this README if you want to show the UI.)

---

## Installation

- If this is a browser extension: load it as an unpacked extension in Chrome/Edge/Firefox Developer Edition (see your browser docs for "Load unpacked").
- If this is a static page: host the files on any static server and set the page as your new tab or homepage.

---

## Using CyberTab

Bookmarks
- Add bookmarks via the + button in the bookmarks section or by right-clicking an empty tile and choosing "Add".
- Reorder bookmarks by dragging tiles around. You can also create folders to group related links.
- Click a tile to open the site in a new tab (or the current tab, depending on your settings).

Search engines
- Use the main search bar to query the web. A small dropdown on the left of the bar shows the active search engine.
- Click the dropdown to switch engines (Google, DuckDuckGo, Bing, etc.).
- Add a custom search engine from Settings by supplying the search URL template (for example: https://www.example.com/search?q=%s).

Settings
- Access settings via the gear icon. From there you can:
  - Choose the default search engine.
  - Manage bookmarks and folders.
  - Toggle animations and neon glow intensity.
  - Import/export your bookmarks and settings.

---

## Customization & Theming

CyberTab uses CSS variables for its neon-black aesthetic. To tweak the look, edit the variables in the theme file or through the Settings panel:

- --bg: background color (default: near-black)
- --neon-1 / --neon-2: primary neon accent colors
- --tile-glow: shadow/glow strength for tiles

Pro tip: lower the glow value if you prefer a more subtle look or increase for a dramatic neon effect.

---

## Privacy

CyberTab is designed to be local-first. By default it:
- Stores bookmarks and settings locally in your browser (localStorage or extension storage).
- Does not send browsing data or telemetry to external servers.

If you add third-party search engines or enable optional features that fetch remote resources, review those services' privacy policies.

---

## Contributing

Contributions are welcome! If you'd like to help:
- Open an issue to propose features or report bugs.
- Fork the repo, make changes, and submit a pull request.
- Keep UI/UX changes consistent with the neon-black theme.

Please include screenshots and a short description of the change in your PR.

---

## Development notes

- The UI is built with simple HTML/CSS/JS (no heavy framework) so it’s easy to edit and extend.
- Search engine templates follow the pattern: replace the query with `%s` (e.g. `https://duckduckgo.com/?q=%s`).
- If you want to change default bookmarks or search engines in the source, look for the settings or data file in the project (commonly `src/`, `data/`, or `config/`).

---

## License

Include your license here (e.g., MIT). If you don't want a license, change this section accordingly.

---

Enjoy your neon-black new-tab. If you'd like, I can add example screenshots, a contrib guide, or a quick settings walkthrough next.
