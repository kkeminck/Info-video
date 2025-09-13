# notbad — Video Tabs (V1-1)

Minimal, closeable “window” tabs that autoplay looping videos. Tuned for Readymag but runnable as a plain static page.

## Quick start (local)
Open `index.html` in a browser. No build step required.

## Deploy to GitHub Pages
1. Create a repo (e.g. `notbad-video-tabs`).
2. Add these files, commit, and push to `main`.
3. In **Settings → Pages**, set **Source** to **Deploy from a branch**, **Branch**: `main` / `/ (root)`.
4. Wait for Pages to build; your demo will be live at `https://<user>.github.io/notbad-video-tabs/`.

## Readymag usage
Paste only the section between `<!-- === V1-1 widget start === -->` and `<!-- === V1-1 widget end === -->` into a Code widget. The widget frame acts as the container.

## Tuning
- **Count:** change `MAX_DESKTOP` / `MAX_MOBILE`.
- **Size range:** `DESKTOP_MIN/MAX`, `MOBILE_MIN/MAX` (fractions of container width).
- **Spread:** `GAP_PCT_W` (0.12 = 12% of container width minimal spacing). Increase for more separation.
- **Edge margin:** `EDGE_MARGIN` keeps windows off edges.

## License
MIT
