# extreme-weather-impacts-in-texas
Repository for EDS 233 Homework 4: Identifying the impacts of extreme weather

## Identifying the Impacts of Extreme Weather: 2021 Texas Power Crisis
This repository contains Assignment 4 for EDS 223 Geospatial Analysis & Remote Sensing. This assignment uses remotely sensed light intensity around Houston, Texas to visualise the impact of severe weather caused by the polar votex in February of 2021. Light data (VIIRS) was accessed via NASA's Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC). The road shapefile was accessed from Geofabrik's download sites for OpenStreepMap (OSM), which allowed for preparation of a GeoPackage containing roads in the Houston area. And data on buildings was also obtained from OpenStreepMap (OSM), which was again downloaded from Geofabrik and prepared a GeoPackage for houses in the Houston metropolitan area. 

## Repository Contents
 - **data/** 
     - data/VNP46A1/VNP46A1/VNP46A1.A2021038.h08v05.001.2021039064328.tif
     - data/VNP46A1/VNP46A1/VNP46A1.A2021038.h08v06.001.2021039064329.tif
     - data/VNP46A1/VNP46A1/VNP46A1.A2021047.h08v05.001.2021048091106.tif
     - data/VNP46A1/VNP46A1/VNP46A1.A2021047.h08v06.001.2021048091105.tif
     - data/gis_osm_buildings_a_free_1.gpkg.zip
     - data/gis_osm_roads_free_1.gpkg.zip
 - **texas-extreme-weather.qmd** contains code to create maps of night light intensity before and after blackouts and of buildings/residences which experienced blackouts; renders to a .pdf.
 - **.gitignore**
 - **README.md**

## Contributors 
[Roshan Andres Nair](https://github.com/roshananair)

## References
1. NASA VIIRS Land Science Investigator-Led Processing System. (2019). VIIRS/NPP Daily Gridded Day Night Band 500m Linear Lat Lon Grid Night (Version 001) [VNP46A1]. NASA Level-1 and Atmosphere Archive & Distribution System Distributed Active Archive Center (LAADS DAAC). https://ladsweb.modaps.eosdis.nasa.gov/

2. Geofabrik GmbH. (2018). OpenStreetMap data extracts [gis_osm_roads_free_1.gpkg]. https://download.geofabrik.de/

3. Geofabrik GmbH. (2018). OpenStreetMap data extracts [gis_osm_buildings_a_free_1.gpkg]. https://download.geofabrik.de/