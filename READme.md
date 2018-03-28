# file_combine.Rmd

This R markdown file is setup to import TT and VMT raw data, processed weather data and linear referenced crash data.

The crash data and station data is first linear referenced in ArcGIS. It then is imported and can be filtered.

The script first combines and cleans all of the TT and VMT datasets. 
It also imports and cleans the Weather and Crash data.

For each desired segment, a starting and ending MP is provided along with the time bins. 
The scripts then filter the TT and VMT datasets and then merge the Crash and Weather datasets to provide one output csv file.


