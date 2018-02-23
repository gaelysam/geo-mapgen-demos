# Geo Mapgen Demos
This repository contains land databases for my Minetest mod [Geo Mapgen](https://github.com/Gael-de-Sailly/geo-mapgen). This mod comes with a Python tool that converts raw elevation / land cover data into a database, that is read on map generation. However I can understand that this may be tedious for just generating one world, and it's perhaps more convenient to directly have access to the database. So I'll make here a collection of my favorite maps. If you want to add a map, please ask me on the [forum topic](https://forum.minetest.net/viewtopic.php?f=9&t=19387) or by forum PM.

## Using the maps
- Download and install [Geo Mapgen](https://github.com/Gael-de-Sailly/geo-mapgen)
- Create a blank Minetest world and enable `geo_mapgen` mod. Don't start the game.
- Copy your desired data file from this repository to your Minetest world folder, and rename it `heightmap.dat`.
- Start the game and enjoy!

## The maps!
For now, there is only one map, but the goal is to group as many ones as possible.

### World 2km
Using [NOAA Global DEM](https://ngdc.noaa.gov/mgg/topo/globe.html) for elevation and [MODIS-based Global Land Cover](https://landcover.usgs.gov/global_climatology.php) for biomes.
- Projection: Mercator
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
![France](https://user-images.githubusercontent.com/6905002/36617435-b68915ac-18e7-11e8-9436-95cb67dd2ac4.png)
