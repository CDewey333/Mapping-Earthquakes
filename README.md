Mapping Earthquakes
Creating interactive maps using Leaflet.js library, Javascript, and HTML to retrieve earthquake information from a GeoJSON file and map out the results in a visual design.
Summary
The purpose of this assignment is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. We used the USGS website (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven days. The data is then added to a map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts are built using JavaScript and D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We then used Leaflet library to plot the data on a Mapbox style map through an API request. We made it interactive by adding visualization for different map styles, creating layers to display tectonic plates, and listing earthquake magnitude and location information.
Results
Map in Street view showing all earthquakes and tectonic plates
 
Map with added 'Major Earthquakes' filter
 
Added third tile layer 'Dark'
