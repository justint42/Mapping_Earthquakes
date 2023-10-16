# Mapping_Earthquakes

## Purpose

This project will utilize D3.js and MapBox API to create an interactive global earthquake map with street map, satellite, and dark map layer options. Earthquake data in GeoJSON format will be requested from the USGS API to plot all magnitude 4.5+ quakes over the past 30 days.

The map will display earthquake locations with circle markers sized by magnitude. A color scale will indicate shallow and deep quakes. On click, popups will show timestamp, location, magnitude, and depth. A slider will filter the date range from 1-30 days.

Users can toggle between light, dark, and satellite map layers using controls provided by MapBox. There will also be options to display tectonic plate boundaries and filter only major quakes above magnitude 7 with prominent red circle markers.

The goal is an educational earthquake visualization that illustrates global seismic patterns and plate tectonics relationships. Interactive features like layer toggling, date filtering, and popups will enable in-depth exploration.
