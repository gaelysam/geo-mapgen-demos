# Geo Mapgen Demos
This repository contains land databases for my Minetest mod [Geo Mapgen](https://github.com/Gael-de-Sailly/geo-mapgen). This mod comes with a Python tool that converts raw elevation / land cover data into a database, that is read on map generation. However I can understand that this may be tedious for just generating one world, and it's perhaps more convenient to directly have access to the database. So I'll make here a collection of my favorite maps. If you want to add a map, please ask me on the [forum topic](https://forum.minetest.net/viewtopic.php?f=9&t=19387) or by forum PM.

## Using the maps
- Download and install [Geo Mapgen](https://github.com/Gael-de-Sailly/geo-mapgen)
- Create a blank Minetest world and enable `geo_mapgen` mod. Don't start the game.
- Copy your desired data file from this repository to your Minetest world folder, and rename it `heightmap.dat`.
- Start the game and enjoy!

## The maps!
Currently 2 maps are available.

### World 2km
Map of the whole world. Elevation (but not bathymetry) and biomes.
![France](https://user-images.githubusercontent.com/6905002/36617435-b68915ac-18e7-11e8-9436-95cb67dd2ac4.png)
- Projection: Mercator (EPSG:3857)
- Coverage: Worldwide (85°N to 85°S)
- Size: 20037x20037
- Elevation data source: [NOAA Global DEM](https://ngdc.noaa.gov/mgg/topo/globe.html)
- Land cover data source: [MODIS-based Global Land Cover](https://landcover.usgs.gov/global_climatology.php)
- Horizontal resolution:
  - 1 node = 2000m at equator
  - 1 node = 1414m at 45°N/S
  - 1 node = 1000m at 60°N/S
- Vertical resolution: 1 node = 200m
- File size: 24.8 MB
- **Download: [world_2km.dat](https://github.com/Gael-de-Sailly/geo-mapgen-demos/blob/master/world_2km.dat?raw=true)**

### Alps 80m
Large rectangle around the Alps, with high resolution.
![Mont Blanc](https://user-images.githubusercontent.com/6905002/36748401-0b8d481c-1bf8-11e8-8a11-945b1dd2ab4d.png)
- Projection: Mercator (EPSG:3857)
- Coverage: 5°E to 15°E, 40°N to 50°N
  - Full Switzerland
  - North of Italy
  - East of France
  - South of Germany
  - West of Austria and Slovenia
- Size: 9840x13969
- Elevation data source: [SRTM](http://srtm.csi.cgiar.org/)
- Land cover data source: [CORINE Land Cover](https://land.copernicus.eu/pan-european/corine-land-cover/clc-2012)
- Horizontal resolution: 1 node = 80m
- Vertical resolution: 1 node = 40m
- File size: 30.6 MB
- **Download: [alps_80m.dat](https://github.com/Gael-de-Sailly/geo-mapgen-demos/blob/master/alps_80m.dat?raw=true)**
