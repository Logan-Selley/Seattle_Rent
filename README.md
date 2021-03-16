# Seattle Rent and Zoning

``` css
    A set of two webmaps that attempt to illustrate both Seattle rent costs and their relative distribution as well as offer some additional insight into why areas are priced the way they are beyond just simple demand. 
    
    The first map aims to show the distribution of Seattle rent prices for housing sizes ranging from studio to 3 bedrooms as well as the overall average for the recognized neighborhood. The second map depicts Seattle zoning, which has an immense effect on not just what kind of housing an area has, but the number of units in an area that may be available. 

    For additional context and to add more potential uses, overlays have been added for both maps that include public transit routes for both King County Metro and the Sound Transit Link Light Rail as well as zones that have been designated for Mandatory Housing Affordability where new developments in these upzoned areas must contribute to affordable housing which could offer additional insight. 
```

## Goal

> Provide people the tools to understand Seattle housing costs and hopefully emphasize the need for continued upzoning for additional density to accomodate for rising demand and continued increasing prices

## Data Sources

### [City Clerk Neighborhoods](https://data-seattlecitygis.opendata.arcgis.com/datasets/city-clerk-neighborhoods?geometry=-123.248%2C47.450%2C-121.018%2C47.774)

> Shapefile of Seattle neighborhoods as measured by the city clerk in 2018 from Seattle Geodata

### [Zoning - Generalized](https://data-seattlecitygis.opendata.arcgis.com/datasets/dc24930c704a4ad0bb5af952ee28eb82_11/data?geometry=-123.453%2C47.454%2C-121.223%2C47.778)

> Shapefile of Seattle Zoning with data from the Office of Planning & Community Development, last updated in 2019 and sourced from Seattle Geodata

### [Mandatory Housing Affordability (MHA) Zones](https://data-seattlecitygis.opendata.arcgis.com/datasets/cce94a62698640b59031ae35292acfe5_0?geometry=-123.314%2C47.454%2C-121.084%2C47.778)

> Zoning areas where MHA requirements apply to new development as of late 2020 with data from the Office of Planning & Community Development, sourced from Seattle Geodata

### [Transit Routes for King County Metro](https://gis-kingcounty.opendata.arcgis.com/datasets/transit-routes-for-king-county-metro-transitroute-line?geometry=-122.443%2C47.654%2C-122.164%2C47.695)

> Shapefile of King County Metro's bus lines throughout King County sourced from King County GIS Open Data

### [SoundTransit Open Transit Data](https://www.soundtransit.org/help-contacts/business-information/open-transit-data-otd/otd-downloads)

> GIS data for all of Sound Transit's bus and rail services

### [RentCafe Seattle](https://www.rentcafe.com/average-rent-market-trends/us/wa/seattle/)

> Data used to create a table for neighborhood wide average rents for Seattle

### [Zumper Seattle](https://www.zumper.com/rent-research/seattle-wa)

> Data used to create a table for specific average rents based on housing size for Seattle

## Applied Libraries

- [leafletjs](https://leafletjs.com/)
- [Bootstrap](https://getbootstrap.com/)
- [chroma.js](https://gka.github.io/chroma.js/)
- [CartoBasemaps](https://carto.com/basemaps/)
- [leaflet-ajax](https://cdnjs.com/libraries/leaflet-ajax)