# Where are NYC restaurant locations?

Dot map of NYC restaurants that you can filter by borough and cuisine. Restaurants at the same coordinates share one marker.

This repo only has the built site, which is served with GitHub Pages.

## Data

- [DOHMH restaurant inspection results](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data) from NYC Open Data, downloaded on 25 October 2026.
- Processing: one row kept per restaurant (CAMIS) and rows without coordinates removed. The result is `data/restaurants.json`.
- Basemap: [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).

## License

The code is MIT (see `LICENSE`). Leaflet is BSD 2-Clause (see `THIRD-PARTY-LICENSES.txt`). The data keeps the terms of NYC Open Data.
