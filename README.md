shell_scripts
=============

bash shell scripts
for batch geoprocessing spatial data using [OGR2OGR](http://www.gdal.org/ogr2ogr.html)

## Requirements
Install FWTools (I used the Linux 64-bit version which is [here](http://fwtools.maptools.org/linux-experimental.html).  

Make sure ogr2ogr is working in command line with basic command: `ogr2ogr`

I suppose you could just add the shell_scripts directory to your `PATH`, but I just run the commands with the full file path.

## Reference Material
These resources have helped me a lot in building the `ogr2ogr` batch commands:
* [Directory of Spatial Reference Systems (SRS)](http://spatialreference.org/ref/)
  * FYI, GitHub currently likes (i.e., requires) `urn:ogc:def:crs:OGC:1.3:CRS84` for displaying geoJSON.
* [List of OGR-supported Vector Formats](http://www.gdal.org/ogr/ogr_formats.html)...*so many options!*



## Scripts
* [clip-extent-project.sh](#clip-extent-projectsh)
* [clip-raster-to-shp.sh](#clip-raster-to-shpsh)
* [clip-to-polygon.sh](#clip-to-polygonsh)
* [geojson-to-shp.sh](#geojson-to-shpsh)
* [get-extent.sh](#get-extentsh)
* [gpx-to-shp.sh](#gpx-to-shpsh)
* [grep-find-replace.sh](#grep-find-replacesh)
* [merge.sh](#mergesh)
* [project-google.sh](#project-googlesh)
* [project-mercator.sh](#project-mercatorsh)
* [project-wgs84.sh](#project-wgs84sh)
* [rename-files-gis-friendly.sh](#rename-files-gis-friendlysh)
* [separate-roads-by-type.sh](#separate-roads-by-typesh)
* [separate-roads-by-type-skeletron.sh](#separate-roads-by-type-skeletronsh)


### clip-extent-project.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### clip-raster-to-shp.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### clip-to-polygon.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### geojson-to-shp.sh
#### Description
This script will export all .geojson files in a directory to .shp files in a specified subdirectory
#### Supported Types
`.geojson`
#### Usage
`cd` to the directory of `.geojson` files you want to convert

`./$SCRIPTHOME/geojson-to-shp.sh`
#### Sample Output
Writes new files to a `data` subdirectory.
### get-extent.sh
#### Description
This does xyz for abc.
#### Supported Types
`.shp`
#### Usage
`./get-extent.sh $DIR/$FILE`
#### Sample Output
`-84.391994 33.758135 -84.376599 33.754353`
### gpx-to-shp.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### grep-find-replace.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### merge.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### project-google.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### project-mercator.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### project-wgs84.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### rename-files-gis-friendly.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### separate-roads-by-type.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### separate-roads-by-type-skeletron.sh
#### Description
This does xyz for abc.
#### Supported Types
`.abc`
#### Usage
`./xxx_yyy.sh $ARGS`
#### Sample Output
`test`
### sshp-to-geojson.sh
#### Description
This converts all shapefiles in a directory `$DIR1` into geoJSON files in `$DIR2`.  If `$DIR1` is not specified, the script looks in the present working directory.  If `$DIR2` is not specificied, the script will place the new geoJSON files in a new subdirectory called `geojson`.
#### Supported Types
`.shp`
#### Usage
`./shp-to-geojson.sh $DIR1 $DIR2`
#### Sample Output
`converting file: /data/bike_lanes.shp...`

