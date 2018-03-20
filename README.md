# Humanitarian OpenStreetMap

This repository contains my contributions to OpenStreetMap.
As a part of contributing to OSM i have succesfully done the following:
1) Create geojson points 
2) Set up my own vector tile server using Docker
3) extract OSM data
4) visualise map 

## The repository contains the following files:

## 1) Geojson files
   places.geojson , dataset1.geojson and stationas.geojson
   These files contain Geojson points that can be incorporated to create a layer of points on a map.
   It was created with the help of MapboxGL.I learnt how map layers are specified via geojson files.
   
## 2) Docker 
   I started on the project by understanding how open street maps work end to end and also extracted OSM data for the map.
   I installed Docker and set up a map server locally.
   Here are the step by step instructions i followed to achieve the same
   https://ananyaarun.github.io/Docker
   The folder openmaptiles contains all the tiles downloaded after the succesful installation.
   
## 3) First map visualisation
   I created a map with an additional layer of city infrastructure specified by me. Each city marker has clickable link with a pop
   up which links to a wiki page. Multiple markers are used e.g. Airport, Harbor.
   https://ananyaarun.github.io/OSM2
   
## 4) Second map visualisation
   I used the leaflet library to achieve a configurable layer. This example allows the user to select the basic theme.
   (grayscale or streets) and provides a select button to show or hide the layer of cities. With a single click, the user can make 
   the layer visible.
   https://ananyaarun.github.io/OSM3
   
## 5) Third map visualisation
   I used Mapbox.js library to display a map with two layers - one showing urban areas and one showing ports. I implemted
   displaying geojson data from an external public URL
   https://ananyaarun.github.io/OSM4 


