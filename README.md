# tailout-data

Daily river-conditions snapshot used by the Tailout app, rebuilt every morning at 5 AM Central.

- `tailout-daily-v1.json.deflate`: compact (raw DEFLATE) JSON with each water's conditions rating, flow, water temperature, data source and quality tier.
- `tailout-daily-v1.meta.json`: when it was generated, how many waters it covers.

Served by GitHub Pages at https://charliebryan-dot.github.io/tailout-data/tailout-daily-v1.json.deflate

## Data credit

Streamflow and water-temperature readings come from the U.S. Geological Survey (USGS) Water Data for the Nation,
https://waterdata.usgs.gov/ (USGS Water Data API). USGS data are public domain; provisional data are subject to revision.
This project is not affiliated with or endorsed by USGS.
