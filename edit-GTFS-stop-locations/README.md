# edit-GTFS-stop-locations

The Edit GTFS Stop Locations toolbox is a set of python script tools that allow you to edit your GTFS public transit stop locations in ArcMap.  It creates a feature class from your current GTFS stops.txt file so you can edit the stop locations and/or attributes using the ArcMap editing tools.  When you have finished editing your stops, the tool will generate a new GTFS stops.txt file that incorporates your changes.

## Features
* Editing - Edit GTFS public transit stops in ArcMap
* ArcGIS toolbox - No coding is required to use this tool.  Just add the toolbox to ArcMap and use the tools like any other geoprocessing tools.

## Instructions

1. To simply use the tool, download the latest release and follow the included User's Guide.
2. If you want to play with the code, fork it and have fun.

## Requirements

* ArcMap 10.1 or higher or ArcGIS Pro. *This tool is deprecated in ArcGIS Pro 2.2 and higher.  To edit your GTFS stop locations in ArcGIS Pro 2.2 and higher, please use the [GTFS Stops To Features](http://pro.arcgis.com/en/pro-app/tool-reference/conversion/gtfs-stops-to-features.htm) and [Features To GTFS Stops](http://pro.arcgis.com/en/pro-app/tool-reference/conversion/features-to-gtfs-stops.htm) tools in the Conversion Tools toolbox.*
* GTFS stops.txt file you wish to edit

## Resources

* [User's Guide](https://github.com/ArcGIS/public-transit-tools/blob/master/edit-GTFS-stop-locations/UsersGuide.md)
* [GTFS specification](https://github.com/google/transit/blob/master/gtfs/spec/en/reference.md)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue, or post a question in the [Esri Community forums](https://community.esri.com/t5/public-transit-questions/bd-p/public-transit-questions).

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2018 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](../License.txt?raw=true) file.