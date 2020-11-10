# osm_server_update
Simple shell script used for updating an Open Street Maps server.<p>
Downloads the latest available raw OSM data for the US.<br>
Imports the new data into a postgres database.<br>
Restarts the render service and re-renders the new tiles.<br>

The variables can be modified to fit your usage.  This script is written for a specific use-case in our environment, please check all PATH variables.  I take no responsibility for any potentional harm cause by improper usage of this code.<br>
This script applies to an OSM map server that was built using [this](https://switch2osm.org/serving-tiles/manually-building-a-tile-server-18-04-lts/) guide on Ubuntu 18.04.<br>
<p>
Trey Richbourg 11/10/2020