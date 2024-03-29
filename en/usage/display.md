# Add a data to the map with the Isogeo plugin

To add a data directly to the map canvas, let's take a look to the options available in the "Add" column.

Here come the different use cases:

- The dataset can be added through different options. User choose its preferred option in the drop-down list.

![](https://raw.githubusercontent.com/isogeo/isogeo-plugin-qgis/master/img/search_results_add_OK_multi_en.png "Data can be added through multiple ways")

- The dataset can be added through only one way. The column "Add" is a button.

![](https://raw.githubusercontent.com/isogeo/isogeo-plugin-qgis/master/img/search_results_addOk_one_en.png "Data can be added through one way")

- The dataset can't be added: file is not reachable and any correct webservice is linked.

![](https://raw.githubusercontent.com/isogeo/isogeo-plugin-qgis/master/img/search_results_addNot_en.png "Unable to add data - check criterias")
___

## Criteria

### File data

Metadata field `Resource location has to contain the absolute path to the datafile.

This path must be reachable:
* by the system user who launched QGIS (read);
* from the machine if the data is located on a local network.

#### Supported formats

##### Vector

- DXF
- DGN
- Esri FileGDB
- Esri shapefile
- MapInfo tab

##### Raster

- ECW
- Esri ascii grid
- Geotiff
- Intergraph gdb
- JPEG
- PNG
- XYZ

### PostGIS

A PostGIS table can be added when:

- the connection to the database has been already set in QGIS
- the option "Save username and password" has been choosen
- the metadata has been created by the Isogeo Scan

### Geographic webservices

Plugin supports webservices layers which have been associated to metadata.

#### Supported services

- Web Feature Service (WFS)
- Web Map Service (WMS)
- Web Map Tile Service (WMTS)

> **Important note**
> Be careful, if service layer title, description or style name contains any special characters, it won't be possible to display it. It's a QGIS issue and related to a bad encoding management in PyQGIS.
