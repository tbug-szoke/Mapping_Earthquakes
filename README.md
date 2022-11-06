# Mapping Earthquakes

## Overview of Project

In this project, we used the Leaflet.js API, to populate a map with GeoJSON earthquake data - in two layers: one showing all earthquakes and one showing only major earthquakes - for the past 7 days. The GeoJSON data was retrieved from the [US Geological Survey Earthquake Hazards site](https://earthquake.usgs.gov/). On the map, each earthquake has been visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. When the marker is clicked, a popup marker shows the magnitude and location of the earthquake. In addition, we added tectonic plate GeoJSON data from a [Github repository](https://github.com/fraxen/tectonicplates).

On viewing the map, a user can select one of three map format layers:
- the default 'streets' map
- an optional 'satellite' map
- or an optional 'night' map
