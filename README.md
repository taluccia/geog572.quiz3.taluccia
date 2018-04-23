# geog572.quiz3.taluccia

This repository contains a readme file and an assets folder. Within the assets folder there are three files:

- R10252.geojson (geojson file from original shape file)
- R10252_simplified (simplified geojson)
- R10252_topo.json (converted R10252.geojson to topojson)


The R10252 is a wildfire identification number, and the files shared here are the wildfire perimeter for fire number R10252. 

| File                  | Size   |
| --------------------- | ------ |
| R10252.geojson        | 20.5KB |
| R10252_simplifiedjson | 5.4KB  |
| R10252_topo.json      | 2.15KB |




The R10252.geojson was converted from a shapefile. The projection was maintained as EPSG:4326, WGS 84.

I took the file R10252.geojson and simplified into R10252_simplified.json. I used [map shaper](https://www.mapshaper.org ) to simplify. I applied a visvalingam/weighted area with prevent shape removal. I simplified it down to 30%.

I also used [map shaper](https://www.mapshaper.org ) to convert the simplified geojson, R10252_simplified.geojson to a topojson. 

Each of these steps greatly reduced the file size, which are listed in the table above. 

### 
