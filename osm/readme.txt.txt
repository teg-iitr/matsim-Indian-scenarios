- OSM file is downloaded from https://download.geofabrik.de/asia/india.html on 29.10.2018.
-  Install osmosis (see instructions here: https://wiki.openstreetmap.org/wiki/Osmosis/Quick_Install_(Windows) ) and set the OSMOSIS to ENV_PATH. 
- See instructions in Section 7.2.1 of MATSim book.
- Run the following command in powershell.

osmosis --read-pbf file="raw/india-latest.osm.pbf" --bounding-box left=74.8076 right=76.5049 top=27.9721 bottom=26.3101 completeWays-true --used-node --write-xml file="extracted/jaipur_bb-box.osm"


- Install JOSM and check if extracted file looks fine.

- Use MATSim plugin to export the network or use script to create MATSim network.
