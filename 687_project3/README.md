## Final dashboard: Pulling it all together

Up to this point, I have developed a dasboard that incorporates an interective map, interective graphs, and dynamic visalization of plots. For the final map, I would like to incorporate functionaility to compare canopy data across three cities. This will involve adding new geographic data and a dynamic zoom function to the map.

### Data
The final version of this dashboard will feature tree canopy types summarized by city neighborhoods of three cities. City neighborhoods were chosen as unit for analysis as they are used in studies by the Batimore Ecosystem Study and USDA Forest Service.

| Region        | Data          | Link          |
| ------------- | ------------- | ------------- |
| New York City | Polygon       | <https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas-NTA-/cpf4-rkhq/>
| Philadelphia  | Polygon       | <https://www.opendataphilly.org/dataset/philadelphia-neighborhoods/>
| Baltimore     | Polygon       | <https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-bes.5000.1/>

The canopy data that used for this project is derived from high resolution land cover data developed by the University of Vermont.
This map product will give the user ability to interpret modified canopy layers representing canopy edge, interior, and corridor that were developed using a spatial pattern analysis tool and other methods developed and implemented by Professor Baker and myself.

| Region        | Resolution    | Year         | Link          |
| ------------- | ------------- |------------- | ------------- |
| Baltimore     | 2 ft          | 2007         | <https://catalog.data.gov/dataset/high-resolution-land-cover-baltimore-county-metro-area-maryland>  |
| Philadelphia  | 0.999 ft      | 2008         | <https://catalog.data.gov/dataset/high-resolution-landcover-philadelphia-pa-2008>  |
| New York City | 3 ft          | 2010         | <https://data.cityofnewyork.us/Environment/Landcover-Raster-Data-2010-3ft-Resolution/9auy-76zt>  |


### Analysis

Like the analysis performed for the Baltimore map, canopy summaries will be computed for New York City and Philadelphia neighborhoods. The tabulate areas tool in ArcGIS will be used to determine the percent cover of canopy variants per neighborhood. This data will be appanded to neighborhood polygon layers and exported with the web map.

### Output
Improving upon the past version of the dasboard, data for New York and Philadelphia will be added to the map. Functionality will be added so that the user can click on a desired region and view mapped neighborhods and canopy for that city. Users will be able to hover over neighborhoods of interest to view statistics on percent canopy cover.
