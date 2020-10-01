# Louisiana Election Shapefiles
This shapefile was obtained from the Louisiana House of Representatives and processed by members of the Metric Geometry and Gerrymandering Group (MGGG).

## Sources
The Maine precinct shapefile was obtained from the [Louisiana House of Representatives](https://house.louisiana.gov/h_redistricting2011/default_LouisianaPrecinctShapefiles.htm). This shapefile uses the 2018 precincts.Election data come from the [Louisiana Secretary of State](https://voterportal.sos.la.gov/Graphical). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile and enacted districts for Louisiana were downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).


## Processing
Some merging of precincts in the tabular election data and precinct shapefile were necessary to join election results for multiple years onto 2018 precinct boundaries. Data from early and absentee votes reported at the state level were disaggregated by voting age population. Because of data reporting and processing, a few precincts cross county boundaries. Demographic data were aggregated from the block level using MGGG’s proration software. Congressional and state legislative district IDs were also assigned to precincts using this package.


## Metadata
* `GEOID`: GEOID
* `STATE`: State
* `STATEFP`: State FIPS code
* `COUNTY`: County name
* `COUNTYFP`: County FIPS code
* `Precinct`: Precinct name
* `CODE`: Precinct code

*	`PRES16D`: Number of votes for 2016 Democratic presidential candidate, with absentee votes
*	`PRES16R`: Number of votes for 2016 Republican presidential candidate, with absentee votes
*	`USH16D`: Number of votes for 2016 Democratic US House candidate, with absentee votes
*	`USH16R`: Number of votes for 2016 Republican US House candidate, with absentee votes
*	`SEN18D`: Number of votes for 2018 Democratic senate candidate, with absentee votes
*	`SEN18R`: Number of votes for 2018 Republican senate candidate, with absentee votes
*	`SEN18I`: Number of votes for 2018 Independent senate candidate, with absentee votes
*	`USH18D`: Number of votes for 2018 Democratic US House candidate, with absentee votes
*	`USH18R`: Number of votes for 2018 Republican US House candidate, with absentee votes
* `
* TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `H_WHITE`: White, hispanic, population from 2010 Decennial Census
* `H_BLACK`: Black, hispanic, population from 2010 Decennial Census
* `H_AMIN`: American Indian and Alaska Native, hispanic, population from 2010 Decennial Census
* `H_ASIAN`: Asian, hispanic, population from 2010 Decennial Census
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population from 2010 Decennial Census
* `H_OTHER`: Other race, hispanic, population from 2010 Decennial Census
* `H_2MORE`: Two or more races, hispanic, population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census
* `CD`: Congressional district
* `HDIST`: State House district
* `SEND`: State Senate district

## Projection
This shapefile uses a Lambert Conformal Conic - Louisiana North projection (ESPG:6476).

## Rating
We give this shapefile a B rating. All data were obtained from the state government and processed by MGGG staff, but there are discrepancies of up to .25% between state-reported vote totals and our summed totals. This does not impact the results of any election.
