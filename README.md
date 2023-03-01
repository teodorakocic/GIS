## GIS

First project: **OpenStreetMap - PostGIS - QGIS**

Second project: **OGC Geospatial Web Services**:

All of the layers that are displayed in the application are taken from the **first project** and the tables from the database (from which queries are created and that way directly we get the access to the layers) have been expanded with more of some available attributes and the filters have been broaden for the purpose of a more complete and compact display of layers in the application.

The installations you need to run this project are:
  - [Apache Tomcat](https://tomcat.apache.org/tomcat-9.0-doc/index.html)
  - [Geoserver](https://geoserver.org/release/stable/)
  - [OpenLayers](https://github.com/openlayers/openlayers/releases/tag/v6.15.0) 
  - [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/download/) (*bootstrap.min.js* and *bootstrap.min.css* files)
  - [jQuery](https://jqueryui.com/download/all/)
  - [Postgis](https://postgis.net/install/)
  - [pgAdmin4](https://www.pgadmin.org/download/)
  
The steps to run the application are as follows:
  1. Run Apache Tomcat 
  2. Run Geoserver
  3. Connect PostGis database with Geoserver / or imort layers into Geoserver
  4. From browser run the script ***index.html***
  
Check out the [demo](assets/webgis.mp4) which shows application's functionalities

