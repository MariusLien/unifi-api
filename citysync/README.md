# CitySync Prototype Preview

The CitySync prototype is a single HTML file (`index.html`) that uses CDN-hosted assets.

## Quick preview

Open the file directly in your browser:

```bash
open citysync/index.html
# or on Linux
xdg-open citysync/index.html
```

## Run with a local web server

If your browser blocks local storage or Tailwind features when opening the file
from disk, serve it with a simple HTTP server:

```bash
cd citysync
python3 -m http.server 4173
```

Then visit http://localhost:4173 in your browser. This preserves routing support
and ensures all assets load correctly.

## Mobile preview tips

Use your browser's responsive design mode or Developer Tools to preview smaller
screen sizes. The layout is responsive down to 360px widths.
