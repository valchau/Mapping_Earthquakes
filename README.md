# Mapping_Earthquakes
module 14

## Basic Project Plan

### Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days, allowing a user to click on an earthquake (represented as circles whose size reflects the magnitude of each earthquake). When a user clicks on an earthquake, the website presents the location and magnitude: 

[location and magntidue example]("one_earthquak.PNG")

### Tasks
To complete this project, I used a URL for GeoJSON earthquake data from the USGS website and retrieved geographical coordinates and the magnitudes of earthquakes for the last seven days. Then I added the data to a map to allow visualization.

### Approach
My approach is to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I also looked at the layout of the GEOJSON data to better understand what is going on and how GEO data is stored. I used the Leaflet library to plot the data on a Mapbox map through an API request (that I finally get the API key for), and it created interactivity for the earthquake data so a user can click on an earthquake and see its magnitide and location. I notice that in San Diego we have a smaller earthquakes with magnitudes between 1 and 2 on the Richter scale, but in other parts of the world such as 

