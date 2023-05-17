City_Clerk_Neighborhoods.geojson was downloaded from [Seattle's Open GeoData website](https://data-seattlecitygis.opendata.arcgis.com/datasets/city-clerk-neighborhoods/explore?location=47.606393%2C-122.308146%2C11.39) on May 17, 2023. I then used https://mapshaper.org/ to convert the GeoJSON to TopoJSON (because the GeoJSON wasn't working properly in Vega-Lite)

The following files were downloaded from https://github.com/seattleio/seattle-boundaries-data on May 17, 2023. I added the 2015 postfix because that's when they were uploaded to GitHub originally on seattleio.
* city-council-districts-2015.geojson
* city-council-districts-2015.topojson
* city-limits-2015.geojson
* neighborhoods-2015.geojson
* zip-codes-2015.geojson