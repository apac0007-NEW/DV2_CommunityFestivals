# Community Festivals in Australia — FIT3179 DV2

This is the complete, flattened GitHub Pages bundle. **All files belong together in the repository root**; do not place them in `css/`, `data/`, or `specs/` folders.

## Included
- `index.html` and `style.css`
- `festival-header.svg` scalable vector header illustration
- 15 Vega-Lite visualisation specifications (3 map idioms plus 12 charts)
- Local JSON and GeoJSON data files used by the charts
- Submission description and helper scripts

## Publish on GitHub Pages
1. Download and extract this ZIP.
2. Upload the **contents** of the extracted folder to the root of the repository that currently works. Do not upload the containing folder itself.
3. Replace existing files when prompted, especially `index.html`, `style.css`, `festival-header.svg`, chart specs, and their data files.
4. Commit the changes.
5. In **Settings → Pages**, publish from the main branch and root (`/`) if it is not already configured.
6. Open the published site and check all three maps and the remaining charts.

## Design and technical notes
- The header artwork is an SVG, not a raster poster; it stays crisp at different sizes.
- The page uses responsive CSS, consistent card spacing, clearer chart-note typography, and more legible Vega-Lite titles, axes and legends.
- Chart and data paths are relative to the repository root. The Vega libraries and fonts load from CDNs, so those external services require an internet connection.
- The three map idioms are choropleth, proportional-symbol map and tile-grid cartogram.
- Before final submission, verify source figures and the boundary GeoJSON edition/licence, and check that the site matches your own sketch and rubric.

See `SUBMISSION_DESCRIPTION.md` for the What/Why/How description and data caveats.
