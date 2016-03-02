## Manitoba Election Constituency Lookup Experiment

Experimenting with using Google Maps address geocoding paired with the [GeoJSON constituency polygons](https://github.com/OpenDemocracyManitoba/Manitoba-Election-GeoJSON-Constituencies).

Given an address the code attempts to find the matching constituency. If found, an alert is fired and the address is marked on the map.

Matching is done using [point within polygon ray-tracing](https://github.com/mattwilliamson/Google-Maps-Point-in-Polygon).

Currently only supports constituencies within Winnipeg.
