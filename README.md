# osm_server_update
Simple shell script to download the latest available raw OSM data for the US.<br>
Import the new data into a postgres database.<br>
Restart the render service and re-render the new tiles.<br>

The variables can be modified to fit your usage, and the wget variable must be adjust as well as it is set to download the data we use.<br>
This script applies to an OSM map server that was built using [this](https://switch2osm.org/serving-tiles/manually-building-a-tile-server-18-04-lts/) guide on Ubuntu 18.04.<br>
<p>
Trey Richbourg 11/10/2020