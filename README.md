# Mapping_Earthquakes

## Objectives

#### Map Layers

Create three different layers that will serve as the base map.

- Using https://api.mapbox.com/styles/ to grab three different maps that will create the base layers.
  - `streets-v11` will be the default layer.
  - `satellite-streets-v11` will be the second layer.
  - `outdoors-v11` will be the third layer.


The next task added the three data layers to the base map.
The data layers would be composed of the three different datasets.
- Recent earthquake [data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) from the USGS website.
- The overlay of tectonic plates can be found [here](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json).
- Earthquakes' whose magnitude registered above a 4.5 was also gathered from the USGS website. Link [here](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson).

