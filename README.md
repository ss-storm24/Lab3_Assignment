# Lab 3 Assignment - ENGO 651 (Advanced Geospatial Topics W22)

## Objectives

- Gain experience with Mapbox Vector Tiles and Mapbox Studio.
- Design a visually appealing map layer.
- Integrate a vector tileset to an existing GeoWeb application.

## Project Summary

The Lab 3 project task was to style a vector tileset on Mapbox's Studio Style Editor using a geospatial dataset from City of Calgary's Open Calgary API. The dataset is for the 2017 Traffic Incidents and will be downloaded as a .csv file. After loading it onto Mapbox, it will be designed and published in order to add it as a map layer on the already built geoweb application from Lab 2.

The main file is application.py which holds the app route. The templates folder holds two files, index.html, the "Home" page with the maps, and layout.html, the foundation for index.html with all the stylesheets and scripts for the functionality of index.html.

### Application
The application.py file consists of an app route that takes users to the home page via index.html. Users will have to set certain environment variables in order for the program to run including:
- set FLASK_APP=application.py
- set FLASK_DEBUG=1
- the DATABASE_URL will have to be set to the provided, commented out, URI that can be found in the application.py file

Once the program is running the user will be able to see the first map and on the top right corner of the map area, they will be able to toggle between the Traffic Incidents map and the basemap.

