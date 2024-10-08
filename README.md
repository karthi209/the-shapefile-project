![repository-open-graph-template-01](https://github.com/karthi209/the-shapefile-project/assets/63890769/4720e71e-f8aa-4aad-b9a5-bf201958b55b)

## Welcome to the shapefile project!
I know this project is named **'the shapefile project'** but it actually does not contain any shape file. I use geoJSON and gpkg (geopackage) formats to store these shapy stuff. I just felt the name 'shape files' has a human touch to it, that's it.

I plan to put all the stuff I hand drew using various sources here. I did not bother to list the sources as of now, will probably do it in the future.

The structure I'm going for is to use two formats (geoJSON for small files and split files and gpkg for large files). geoJSON is a plain text format that can even be opened with a text editor and github too has good support to even track the changes, however it can get quite large with more polygon and stuff very quickly and could slow down your GIS tool if dataset is large. But I still love the simplicity and the ease of viewing. That's why I'm planning to take advantage of both the format as each has it's own advantage.

If you see a file that ends with .geoJSON, you cna view it directly by clicking it in this repo. Github has a nice realtime view that's hosted in Azure. If the file format is .gpkg, then you'll have to use a GIS tool to view it. I would recommend [QGIS](https://qgis.org/), available for Windows, Linux and Mac.
