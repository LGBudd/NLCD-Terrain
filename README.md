# Chicago and Milwaukee Custom Scenery
Custom NLCD scenery for the area covered by Chicago, Milwaukee and the surrounding suburbs

## License
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

The zip archives on the Releases page were created using the TerraGear and TerraGear-GUI programs developed by the FlightGear project. The git repository includes the source data. To download the resulting scenery, go to the Releases page and download the zip archives.

## Chicago and Milwaukee Area Custom Scenery

Custom scenery for the Chicago (KORD) and Milwaukee (KMKE) areas, for the FlightGear Flight Simulator. This includes:
- The airports recommended as of October 2020 from the X-Plane Scenery Gateway
- Area includes scenery between the following coordinates: 
  - min lat 41.5
  - max lat 44.0
  - min lon -89.0
  - max lon -87.0 
- Optional USGS orthophotos around major airports within the included area.
- Groundnets for the major airports within the area (KORD, KMDW, KMKE) have been uploaded to Terrasync and now are included in the FlightGear database.
- Updated NavData for KORD should be downloaded and installed with this custom scenery. The updated airport uses this updated data.

### NOTE: 
This scenery is best when used together with "Champaign" and "Oshkosh and UP" custom scenery. Use of these three custom sceneries together (KORD-KMKE-Custom-Scenery, Champaign-Custom-Scenery and NWI-UPM-Custom-Scenery) will minimize issues at the scenery borders. They also provide a signicant North-South flight area with decent scenery.

### Data Sources

- Airports: X-Plane Scenery Gateway: https://gateway.x-plane.com/
- Landcover: National landcover database (NLCD): https://www.usgs.gov/centers/eros/science/national-land-cover-database
- Elevation: Shuttle Radar Topology Mission 1-arc-second (SRTM-1), void-filled version: https://earthexplorer.usgs.gov/
- Rivers and waterbodies: National Hydrography Dataset (NHD): https://www.usgs.gov/core-science-systems/ngp/national-hydrography
- Buildings, roads, pylons, other objects: OpenStreetMap using osm2city: https://www.openstreetmap.org/ https://osm2city.readthedocs.io/en/latest/
- FlightGear TerraSync objects
- Orthophotos: USGS Orthophotos: https://earthexplorer.usgs.gov/ (**Note:** color correction done by an amateur)

### To Download

To download the custom scenery files, go to the Releases page and download the zip archives.

### To Install

To install:
1) Create a directory on your local hard drive
2) Download Buildings.zip, Objects.zip, Pylons.zip, Roads.zip, Terrain.zip, and Orthophotos,zip 
3) Extract the files into the local directory you've created. 

For example, create a directory called "KORD-KMKE" on your computer. Extract the downloaded files into this directory. 

4) Add this directory to Additional Scenery Folders in the FlightGear GUI (launcher) 
5) To use the custom materials definitions and custom textures created:
    a) Download Illinois-data.zip and extract it. Rename the folder to "data.zip".
    b) Copy this "data" folder, open "$FG_ROOT" and paste. In Windows, this is the data folder within the FlightGear 2020.4 directory. This should result in Illinois.xml residing in the "$FG_ROOT/Materials/regions/" directory and a folder labeled "Illinois" in the "$FG_ROOT/Textures/Terrain/" directory.
 6) Start FlightGear. While on the start-up screen click "Add-ons". Scroll to the "Additional scenery folders" section, the click the plus (+) sign on the right side of the screen. A dialog box will pop up. Browse to the folder you created in step 1. Highlight the folder, then click "Select Folder". Confirm that the folder was added to the bottom of "Additional scenery folders". You can now highlight and move the folder to a higher priority if necessary. 
 7) Make the selections you want to use for your next flight then click "Fly", as usual.
 8) Rendering Options enable OSM buildings, detailed roads and pylons under 

### Southwest Airlines Traffic Files for KMDW
A traffic file for Southwest Airlines flights to and from Chicago Midway Airport (KMDW) were generated. To install the file:
1) extract the .zip file into a temporary directory of your choosing.
2) cut the SWA.xml file and past it into the \FlightGear [version]\data\AI\Traffic\S folder.

## Screenshots

### Approach to Chicago (with orthophotos)
![Chicago Downtown](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/Chicago20210326174334.png)

### Chicago "Loop" (Downtown) (with orthophotos)
![Chicago](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/ChicagoB.png)

### Takeoff from Milwaukee (KMKE) (with orthophotos
![Takeoff from Milwaukee (KMKE)](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/Takeoff%20from%20KMKE%203.png)

### Looking to the South of Milwaukee (with orthophotos)
![South of Milwaukee](https://github.com/LGBudd/KORD-KMKE-Custom-Scenery/blob/master/Screenshots/Looking%20to%20%20the%20South%20from%20Milwaukee.png)
