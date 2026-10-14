# XecLabs website concept

This is a static GitHub Pages-ready site. Keep these files together in the repository root (or publish this directory as the Pages source):

- `index.html` — semantic page structure and page copy
- `styles.css` — responsive visual system
- `script.js` — navigation, portfolio rendering and metric animation
- `projects.json` — editable, structured portfolio content
- `cs/index.html` and `cs/projects.json` — Czech-language version with translated portfolio data
- `assets/hero-network.png` — generated blue data-network artwork used in the hero

The portfolio is loaded from `projects.json` at runtime, so preview the page through a web server such as GitHub Pages rather than opening `index.html` directly as a `file://` URL.

The JSON uses a simple public schema: `schemaVersion`, `organization`, `portfolio[]` (with `id`, `company`, `title`, `category`, `description`, and `outcomes[]`) and `currentInitiatives[]`. Edit the data file to change case studies without changing the layout.

The English page is the default at `/`; the Czech page is available at `/cs/`. The language links are relative, so they work both on a custom domain and on GitHub Pages project URLs.

The copy and results in this concept are based on the supplied XecLabs page source. Please confirm client permissions and figures before publication.
