# geojson
for geojson data - useful in PBI mapping applications (alternative to arcGIS online)
currentkly (13/7/23) we upload to arcGIS and the process to get the url is a bit tricky
(and might use soem arcGIS resouirce - not sure - but this is "zero" cost)

The url that appears to work is 
https://raw.githubusercontent.com/CBG-Health-Research-Ltd/geojson/main/SA2_GCH.geojson
this returns the data to a browser and dosen't throw the CORS error, however layer doesn't appear in PBI

ah - we need to add a field that matches the category field in eth PBO grpahics dataste - will do soon
