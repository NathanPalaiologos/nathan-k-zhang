# Geographic outlines

These static extracts supply vector lines for the portfolio's dotted maps.

- `regional.json`: Natural Earth 1:10m coastline, rivers, and lakes; [public domain](https://www.naturalearthdata.com/about/terms-of-use/).
- Numeric filenames: OpenStreetMap ways around each listed city's GeoNames coordinate; © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Each file records its source date.
- Coordinates use Web Mercator in a 360-unit square, rounded to four decimals. Very close intermediate vertices are omitted. The lines are for illustration, not navigation.

Regenerate with `node scripts/build-explored-geography.mjs` from the repository root. Source responses are cached in the ignored `output/world-map/vectors/` directory; map browsing does not call Overpass or a tile service.
