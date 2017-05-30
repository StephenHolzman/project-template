# Input Folder

The input folder should contain files and documentation exactly as they were retreived from a 3rd party publisher. Any data transformations or modeling should be done by reading these files into other programs, probably from a script in the Analysis folder.

### Do not edit files in this folder

The entire purpose of the input folder is to preserve your data sources.

### Organization

This is more flexible and project dependent. To start, I might organize files in the following hierarchy: 
  
  1. Type
  2. Publisher
  3. Product
  4. Any sub-product series
  5. Year Published
  6. etc...

### Included Examples

I've made folders for three common types of files I want to retrieve from data vendors:

* **data**: This folder would contain files like .csv, .json, .tsv, or .xlsx.
* **shapes**: This folder would contain shapefiles, topojson, or geojson files.
* **text**: This folder should contain text for the purpose of citation or analysis only. Documentation of datasets should be kept in the same place as that data.

### Automate Downloading Data
If possible, write a script to automatically download data and documentation. At the very least, record where and when you downloaded the data in a README.