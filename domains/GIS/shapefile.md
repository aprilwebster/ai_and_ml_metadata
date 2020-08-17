### What is a shapefile?
It's a cluster of files.  All component files have the same filename, but different file extensions.

Three **mandatory** components:
- feature geometry (**.shp**)
- index of the feature geometry (**.shx**)
- feature attribute data (**.dbf**)

Other commonly required files to be able to do analysis:
- projection (**.prj**): coordinate system for the geometric data; essential for accurately integrating more than one shapefile
- metadata (**.xml**): metadata, as used by ArcGIS.
- there are several other files that may be included

#### Metadata
- "GIS metadata documenting important characteristics of the resource found in the Shapefile format such as bounding coordinates, datum, etc. may be included as a .xml file within the file group." (https://www.loc.gov/preservation/digital/formats/fdd/fdd000280.shtml)
- "In ArcGIS, the metadata file is often called metadata.xml and must be stored in the same file directory or project workspace as the rest of the component files in the Shapefile format cluster in order to be used by ArcGIS applications." (https://www.loc.gov/preservation/digital/formats/fdd/fdd000280.shtml)

#### History of the shapefile
- ESRI's Whitepaper introducing the shapefile in July 1998: https://www.esri.com/library/whitepapers/pdfs/shapefile.pdf

### What problem was it designed to address?
- as an open specification for data interoperability among Esri and other software products.


#### Criticism
"As of 2020, with increasing size of datasets and more GIS use and analysis by beginners and non-specialists, the shortcomings of the Shapefile format are increasingly significant. Alternatives include the openly specified OGC GeoPackage and the proprietary ESRI File Geodatabase. Examples of advocacy for stopping use of Shapefile, with lists of problems, include Switch from Shapefile and Why you should use GeoPackage instead of Shapefile." (https://www.loc.gov/preservation/digital/formats/fdd/fdd000280.shtml)
