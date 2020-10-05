# Louisiana Election Shapefiles
This shapefile was obtained from the Louisiana House of Representatives and processed by members of the Metric Geometry and Gerrymandering Group (MGGG).

## Sources
The precinct shapefile was obtained from the [Louisiana House of Representatives](https://house.louisiana.gov/h_redistricting2011/default_LouisianaPrecinctShapefiles.htm). This shapefile uses the 2018 precincts. Election data come from the [Louisiana Secretary of State](https://voterportal.sos.la.gov/Graphical). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile and enacted districts for Louisiana were downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).


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
* `PRES16D`: votes for 2016 US President democratic candidate in the 2016 general election
* `PRES16R`: votes for 2016 US President republican candidate in the 2016 general election
* `SEN16pD1`: votes for democratic candidate Foster Campbell in 2016 US Senate jungle primary
* `SEN16pD2`: votes for democratic candidate Derrick Edwards in 2016 US Senate jungle primary
* `SEN16pD3`: votes for democratic candidate Caroline Fayard in 2016 US Senate jungle primary
* `SEN16pD4`:  votes for democratic candidate Gary Landrieu in 2016 US Senate jungle primary
* `SEN16pD5`:  votes for democratic candidate Vinny Mendoza in 2016 US Senate jungle primary
* `SEN16pD6`:  votes for democratic candidate Josh Pellerin in 2016 US Senate jungle primary
* `SEN16pD7`:  votes for democratic candidate Peter Williams in 2016 US Senate jungle primary
* `SEN16pU1`: votes for unaffiliated candidate Beryl Billot in 2016 US Senate jungle primary
* `SEN16pU2`: votes for unaffiliated candidate Troy Herbert in 2016 US Senate jungle primary
* `SEN16pU3`: votes for unaffiliated candidate William Robert Lang Jr. in 2016 US Senate jungle primary
* `SEN16pR1`: votes for independent candidate Kaitlin Marone in 2016 US Senate jungle primary
* `SEN16pU4`: votes for unaffiliated candidate Gregory Taylor Jr. in 2016 US Senate jungle primary
* `SEN16pU5`: votes for unaffiliated candidate Arden Wells in 2016 US Senate jungle primary
* `SEN16pL1`: votes for libertarian candidate Thomas Clements in 2016 US Senate jungle primary
* `SEN16pL2`: votes for libertarian candidate Le Roy Gillam in 2016 US Senate jungle primary
* `SEN16pR2`:  votes for republican candidate Charles Boustany Jr. in 2016 US Senate jungle primary
* `SEN16pR3`:  votes for republican candidate Joseph Cao in 2016 US Senate jungle primary
* `SEN16pR4`:  votes for republican candidate Donald Crawford in 2016 US Senate jungle primary
* `SEN16pR5`:  votes for republican candidate David Duke in 2016 US Senate jungle primary
* `SEN16pR6`:  votes for republican candidate John Fleming in 2016 US Senate jungle primary
* `SEN16pR7`:  votes for republican candidate John Kennedy in 2016 US Senate jungle primary
* `SEN16pR8`:  votes for republican candidate Rob Maness in 2016 US Senate jungle primary
* `SEN16pR9`:  votes for republican candidate Charles Marsala in 2016 US Senate jungle primary
* `SEN16pR10`:  votes for republican candidate Abhay Patel in 2016 US Senate jungle primary
* `SEN16roD`: votes for US Senate democratic candidate Foster Campbell in the 2016 run-off election
* `SEN16roR`: votes for US Senate republican candidate John Kennedy in the 2016 run-off election
* `SOS18pD1`: votes for democratic candidate Gwen Collins-Greenup  in the 2018 Secretary of State jungle primary
* `SOS18pD2`: votes for democratic candidate Renee Fontenot Free in the 2018 Secretary of State jungle primary
* `SOS18pI`:  votes for independent candidate Matthew Moreau in the 2018 Secretary of State jungle primary
* `SOS18pR1`: votes for republican candidate Kyle Ardoin in the 2018 Secretary of State jungle primary
* `SOS18pR2`: votes for republican candidate Heather Cloud in the 2018 Secretary of State jungle primary
* `SOS18pR3`: votes for republican candidate A.G. Crowe in the 2018 Secretary of State jungle primary
* `SOS18pR4`: votes for republican candidate Rick Edmonds in the 2018 Secretary of State jungle primary
* `SOS18pR5`: votes for republican candidate Thomas Kennedy III in the 2018 Secretary of State jungle primary
* `SOS18pR6`: votes for republican candidate Julie Stokes in the 2018 Secretary of State jungle primary
* `SOS18D`:  votes for Secretary of State democratic candidate Gwen Collins-Greenup in the 2018 special general election
* `SOS18R`:  votes for Secretary of State republican candidate Kyle Ardoin in the 2018 special general election
* `USH16pD1`: votes for US House District 2 democratic candidate Kenneth Cutno in the 2016 jungle primary
* `USH16pD2`: votes for US House District 1 democratic candidate Lee Ann Dugas in the 2016 jungle primary
* `USH16pD3`: votes for US House District 1 democratic candidate Danil Ezekiel Faust in the 2016 jungle primary
* `USH16pD4`:  votes for US House District 2 democratic candidate Kip Holden in the 2016 jungle primary
* `USH16pD5`:  votes for US House District 4 democratic candidate Marshall Jones in the 2016 jungle primary
* `USH16pD6`:  votes for US House District 6 democratic candidate Richard Lieberman in the 2016 jungle primary
* `USH16pD7`:  votes for US House District 3 democratic candidate Jacob "Dorian Phibian" Hebert in the 2016 jungle primary
* `USH16pD8`:  votes for US House District 3 democratic candidate Larry Rader in the 2016 jungle primary
* `USH16pD9`:  votes for US House District 2 democratic candidate Cedric Richmond in the 2016 jungle primary
* `USH16pD10`:  votes for US House District 6 democratic candidate Jermaine Sampson in the 2016 jungle primary
* `USH16pD11`:  votes for US House District 1 democratic candidate Joe Swider in the 2016 jungle primary
* `USH16pG1`:  votes for US House District 1 green party candidate Eliot Barron in the 2016 jungle primary
* `USH16pU1`: votes for US House District 6 unaffiliated candidate Devin Lance Graham in the 2016 jungle primary
* `USH16pU2`: votes for US House District 4 unaffiliated candidate Mark Halverson in the 2016 jungle primary
* `USH16pU3`: votes for US House District 4 unaffiliated candidate Kenneth Krefft in the 2016 jungle primary
* `USH16pU4`: votes for US House District 3 unaffiliated candidate Kenny Scelfo in the 2016 jungle primary
* `USH16pU5`: votes for US House District 1 unaffiliated candidate Chuemai Yang in the 2016 jungle primary
* `USH16pL1`:  votes for US House District 6 libertarian candidate Richard Fontanesi in the 2016 jungle primary
* `USH16pL2`:  votes for US House District 1 libertarian candidate Howard Kearney in the 2016 jungle primary
* `USH16pL3`:  votes for US House District 3 libertarian candidate Guy McLendon in the 2016 jungle primary
* `USH16pR1`:  votes for US House District 5 republican candidate Ralph Abraham in the 2016 jungle primary
* `USH16pR2`:  votes for US House District 3 republican candidate Scott Angelle in the 2016 jungle primary
* `USH16pR3`:  votes for US House District 3 republican candidate Bryan Barrilleaux in the 2016 jungle primary
* `USH16pR4`:  votes for US House District 4 republican candidate Trey Baucum in the 2016 jungle primary
* `USH16pR5`:  votes for US House District 6 republican candidate Robert Lamar Bell in the 2016 jungle primary
* `USH16pR6`:  votes for US House District 5 republican candidate Billy Burkette in the 2016 jungle primary
* `USH16pR7`:  votes for US House District 3 republican candidate Greg Ellison in the 2016 jungle primary
* `USH16pR8`:  votes for US House District 3 republican candidate Brett Geymann in the 2016 jungle primary
* `USH16pR9`:  votes for US House District 6 republican candidate  Garret Graves in the 2016 jungle primary
* `USH16pR10`:  votes for US House District 4 republican candidate Elbert Guillory in the 2016 jungle primary
* `USH16pR11`:  votes for US House District 3 republican candidate Clay Higgins in the 2016 jungle primary
* `USH16pR12`:  votes for US House District 4 republican candidate Oliver Jenkins in the 2016 jungle primary
* `USH16pR13`:  votes for US House District 4 republican candidate Mike Johnson in the 2016 jungle primary
* `USH16pR14`:  votes for US House District 3 republican candidate Gus Rantz in the 2016 jungle primary
* `USH16pR15`:  votes for US House District 3 republican candidate Grover Rees in the 2016 jungle primary
* `USH16pR16`:  votes for US House District 4 republican candidate Rick John in the 2016 jungle primary
* `USH16pR17`:  votes for US House District 1 republican candidate Steve Scalise  in the 2016 jungle primary
* `USH16pR18`:  votes for US House District 3 republican candidate Herman Vidrine in the 2016 jungle primary
* `USH18pD1`: votes for US House District 3 democratic candidate Rob Anderson in the 2018 jungle primary
* `USH18pD2`: votes for US House District 5 democratic candidate Jessee Carlton Fleenor in the 2018 jungle primary
* `USH18pD3`: votes for US House District 6 democratic candidate Justin DeWitt in the 2018 jungle primary
* `USH18pD4`: votes for US House District 1 democratic candidate Lee Ann Dugas in the 2018 jungle primary
* `USH18pD5`: votes for US House District 1 democratic candidate Jim Francis in the 2018 jungle primary
* `USH18pD6`: votes for US House District 3 democratic candidate Mildred Methvin in the 2018 jungle primary
* `USH18pD7`: votes for US House District 3 democratic candidate Larry Rader in the 2018 jungle primary
* `USH18pD8`: votes for US House District 2 democratic candidate Cedric Richmond in the 2018 jungle primary
* `USH18pD9`: votes for US House District 6 democratic candidate Andie Saizan in the 2018 jungle primary
* `USH18pD10`: votes for US House District 1 democratic candidate Tammy Savoie in the 2018 jungle primary
* `USH18pD11`: votes for US House District 3 democratic candidate Verone Thomas in the 2018 jungle primary
* `USH18pD12`: votes for US House District 4 democratic candidate Ryan Trundle in the 2018 jungle primary
* `USH18pI1`: votes for US House District 2 independent candidate Belden Batiste in the 2018 jungle primary
* `USH18pI2`: votes for US House District 5 independent candidate Billy Burkette in the 2018 jungle primary
* `USH18pI3`: votes for US House District 6 independent candidate Devin Lance Graham in the 2018 jungle primary
* `USH18pU1`: votes for US House District 4 unaffiliated candidate Mark Halverson in the 2018 jungle primary
* `USH18pI4`: votes for US House District 1 independent candidate Fredrick Jones in the 2018 jungle primary
* `USH18pU2`: votes for US House District 2 unaffiliated candidate Shawndra Rodriguez in the 2018 jungle primary
* `USH18pU3`: votes for US House District 2 unaffiliated candidate Jesse Schmidt in the 2018 jungle primary
* `USH18pL1`: votes for US House District 3 libertarian candidate Aaron Andrus in the 2018 jungle primary
* `USH18pL2`: votes for US House District 1 libertarian candidate Howard Kearney in the 2018 jungle primary
* `USH18pL3`: votes for US House District 5 libertarian candidate Kyle Randol in the 2018 jungle primary
* `USH18pR1`: votes for US House District 5 republican candidate Ralph Abraham in the 2018 jungle primary
* `USH18pR2`: votes for US House District 6 republican candidate  Garret Graves in the 2018 jungle primary
* `USH18pR3`: votes for US House District 3 republican candidate Josh Guillory in the 2018 jungle primary
* `USH18pR4`: votes for US House District 3 republican candidate Clay Higgins in the 2018 jungle primary
* `USH18pR5`: votes for US House District 4 republican candidate Mike Johnson in the 2018 jungle primary
* `USH18pR6`: votes for US House District 1 republican candidate Steve Scalise  in the 2018 jungle primary
* `AG15R1`: votes for republican candidate James D. "Buddy" Caldwell in the 2015 Attorney General general election
* `AG15R2`: votes for republican candidate Jeff Landry in the 2015 Attorney General general election
* `AG19D`: votes for democratic candidate Ike Jackson, Jr in the 2019 Attorney General election (primary, but no general necessary)
* `AG19R`: votes for republican candidate Jeff Landry in the 2019 Attorney General election (primary, but no general necessary)
* `CAF19pD1`: votes for democratic candidate Marguerite Green in the 2019 Commissioner of Agriculture and Forestry jungle primary
* `CAF19pD2`: votes for democratic candidate Charlie Greer in the 2019 Commissioner of Agriculture and Forestry jungle primary
* `CAF19pD3`: votes for democratic candidate Peter Williams in the 2019 Commissioner of Agriculture and Forestry jungle primary
* `CAF19pR1`: votes for republican candidate Michael G. “Mike” Strain in the 2019 Commissioner of Agriculture and Forestry jungle primary
* `CAF19pR2`: votes for republican candidate Bradley Zaunbrecher in the 2019 Commissioner of Agriculture and Forestry jungle primary
* `CI19pR1`: votes for republican candidate James J. Jim Donelon in the 2019 Commissioner of Insurance jungle primary
* `CI19pR2`: votes for republican candidate Tim Temple in the 2019 Commissioner of Insurance jungle primary
* `GOV15D`: votes for democratic candidate John Bel Edwardsin the 2015 Gubernatorial general election
* `GOV15pD1`: votes for democratic candidate Cary Deaton in the 2015 Gubernatorial jungle primary
* `GOV15pD2`: votes for democratic candidate John Bel Edwards in the 2015 Gubernatorial jungle primary
* `GOV15pD3`: votes for democratic candidate S L Simpson in the 2015 Gubernatorial jungle primary
* `GOV15pR1`: votes for republican candidate Scott A. Angelle in the 2015 Gubernatorial jungle primary
* `GOV15pR2`: votes for republican candidate Jay Dardenne in the 2015 Gubernatorial jungle primary
* `GOV15pR3`: votes for republican candidate David Vitter in the 2015 Gubernatorial jungle primary
* `GOV15pU1`: votes for unaffiliated candidate Beryl Billiot in the 2015 Gubernatorial jungle primary
* `GOV15pU2`: votes for unaffiliated candidate Jeremy JW Odom in the 2015 Gubernatorial jungle primary
* `GOV15pU3`: votes for unaffiliated candidate Eric Paul Orgeron in the 2015 Gubernatorial jungle primary
* `GOV15R`: votes for republican candidate David Vitterin the 2015 Gubernatorial general election
* `GOV19D`: votes for democratic candidate John Bel Edwards in the 2019 Gubernatorial general election
* `GOV19pI`: votes for independent candidate Gary Landrieuin the 2019 Gubernatorial jungle primary
* `GOV19pD1`: votes for democratic candidate Oscar Omar Dantzler in the 2019 Gubernatorial jungle primary
* `GOV19pD2`: votes for democratic candidate John Bel Edwards in the 2019 Gubernatorial jungle primary
* `GOV19pR1`: votes for republican candidate Ralph Abrahamin the 2019 Gubernatorial jungle primary
* `GOV19pR2`: votes for republican candidate Patrick Live Wire Landry in the 2019 Gubernatorial jungle primary
* `GOV19pR3`: votes for republican candidate Eddie Rispone in the 2019 Gubernatorial jungle primary
* `GOV19R`: votes for republican candidate Eddie Rispone in the 2019 Gubernatorial general election
* `LG19D`: votes for democratic candidate Willie Jones in the 2019 Lieutenant governor election (primary, but no general necessary)
* `LG19R`: votes for republican candidate William Billy Nungesser in the 2019 Lieutenant governor election (primary, but no general necessary)
* `SOS15D`: votes for democratic candidate Chris Tyson in the 2015 Secretary of State election (primary, but no general necessary)
* `SOS15R`: votes for republican candidate Tom Schedler in the 2015 Secretary of State election (primary, but no general necessary)
* `SOS19D`: votes for democratic candidate "Gwen" Collins-Greenup in the 2019 Secretary of State general election
* `SOS19R`: votes for republican candidate Kyle Ardoin in the 2019 Secretary of State general election
* `TRE15pR1`: votes for republican candidate John Kennedy in the 2015 Treasurer jungle primary
* `TRE15pR2`: votes for republican candidate Jennifer Treadway in the 2015 Treasurer jungle primary
* `TRE17D`: votes for democratic candidate Derrick Edwards in the 2017 Treasurer general election
* `TRE17pD1`: votes for democratic candidate Derrick Edwards in the 2015 Treasurer jungle primary
* `TRE17pL1`: votes for libertarian candidate Joseph D. Little in the 2017 Treasurer jungle primary
* `TRE17pR1`: votes for republican candidate Angele Davis in the 2017 Treasurer jungle primary
* `TRE17pR2`: votes for republican candidate Terry Hughes in the 2017 Treasurer jungle primary
* `TRE17pR3`: votes for republican candidate Neil Riser in the 2017 Treasurer jungle primary
* `TRE17pR4`: votes for republican candidate John Schroder in the 2017 Treasurer jungle primary
* `TRE17R`: votes for republican candidate John Schroder in the 2017 Treasurer general election
* `TRE19pD`: votes for democratic candidate Derrick Edwards in the 2019 Treasurer jungle primary (no run-off necessary)
* `TRE19pR`: votes for republican candidate John M. Schroder in the 2019 Treasurer jungle primary (no run-off necessary)
* `TRE19pU`: votes for unaffiliated candidate Teresa Kenny in the 2019 Treasurer jungle primary (no run-off necessary)
* `TOTPOP`: Total population from 2010 Decennial Census
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
