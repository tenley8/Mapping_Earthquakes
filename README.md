## Basic Project Plan
## Purpose

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Tasks
To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

## Resources
Data Source: 
config.js
cities.js
majorAirport.json
torontoNeighborhoods.json
torontoRoutes.json
Software: VS code

## Approach
Your approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. You’ll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Summary
- Retrieve data from a GeoJSON file.
- Make API requests to a server to host geographical maps.
- Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
- Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
- Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
- Render maps on a local server.

## Challenge
In this challenge, you’ll add a third map style as an additional tile layer. You'll also add tectonic plate GeoJSON data to the map to illustrate the relationship between the location and frequency of seismic activity and tectonic plates.

## Objectives
The goals of this challenge are for you to:
-  Use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
-  Style the tectonic plate LineString data to stand out on the map.
-   Add the tectonic plate data as an overlay with the earthquake data.
    Add a third map style to allow the user to select from three different maps.
