# Analysis on Landfill Methane Outreach Program (LMOP) 

![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/ced41865-9bc4-4b6b-969d-d92411d363a3)

Image by: Dani Argandona | Unsplash - Free to use under Unsplash License


## Introduction
"The LMOP Landfill and Landfill Gas Energy Project Database (LMOP Database) contains information such as a physical address, latitude, and longitude, owner/operator organization, operational status, year opened, actual or expected closure year, design capacity, amount of waste in place, gas collection system status and landfill gas (LFG) collected amount for 2,637 municipal solid waste landfills. For landfills that report under EPA’s Greenhouse Gas Reporting Program (GHGRP), LMOP cross-references that data set by including GHGRP’s 7-digit Facility Identifier." - LMOP

Reference: https://www.epa.gov/lmop

## Aim: The main goal of this research is to utilize the map to analyze the locations and characteristics of landfills in the United States.

### Data: The data are available from the Environmental Protection Agency (EPA) as referenced here.

## Dataset
“The LMOP Database contains key information about MSW landfills and LFG energy projects in the United States. Information in the LMOP Database is compiled from a variety of sources. Data received for inclusion in the LMOP Database are reviewed for reasonableness and are corroborated via other data sources when possible. Not all data are updated each year. While the Program strives to keep the information as updated and accurate as possible, the database is not exhaustive. The LMOP Database does not include data for every MSW landfill in the United States.” - EPA
![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/64ea74a9-1643-4fdc-a0a4-e3433b1af6f0)

## Data Summary
Using the ‘expss’ function in R to generate baseline statistical tabulations of the data. We generate tabulations to display the state as well as three (3) other waste indicators based on the current status (open, closed). The map can then be used to analyze the data.
![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/10a86a02-8b3a-48f2-8a5b-870a73b1ca88)
#
Watstes Statistics in Summary

![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/d774b468-9ba3-4bf3-880e-d43e2889e199)

## Annual Waste Acceptance Rate (tons) for the United States in 2021.

### Map 
This leaflet map provides an overview of the waste acceptance rate in 2021 across the United States. In order to present the data, it has been divided into color bins with values ranging from 0 to 35,000,000 tons. Selecting various states will allow the user to view the specific acceptance rates for each state. Additionally, there is also a legend provided to indicate the color-coded values that represent different waste acceptance rates.


![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/0655af27-6994-4e4f-a464-45309381ac3e)

## Landfill sustainability (years) in the United States
Although each state has a different population and other factors, we need another indicator to represent landfill capacity more accurately. Using landfill sustainability, we are able to determine how long a state would be able to satisfy its landfill requirements without having to build new sites.

![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/73681278-b7b2-4e12-9802-5b57f65dc217)

### Summary
As a result of the assessment, this describes the two maps which were distinctively generated to indicate each state’s sustainability. The first indicates that Nevada and Utah have great sustainability, whereas the second shows that the New England region, particularly Massachusetts, Rhode Island, and Vermont are experiencing severe problems with refuse disposal.

![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/5f185829-1829-4949-9019-3645567d049e)

## Texas Landfill sustainability in (years)
To better narrow the scope of our analysis to the situation in Texas, where I recently live, then analyze it below. In this case, landfill environmental sustainability will be used as an example. Each of the counties shown here describes the size of their sustainability up until 2021. Few counties have the highest waste disposal facilities sustainability in Texas (TX), along with more than a quarter not listed among the counties in TX having adequate landfill sustainability.

![image](https://github.com/simplyEmmanuel/Leaflet_Maps_in_R/assets/57048981/1c091cf6-3998-4b48-8ec1-d6b5b5596872)

## Results
- We can deduce that the states of Texas, California, Northeast, Southeast, and the Great Lakes have the most trash.

- In comparison to other states, Utah and Nevada are thought to have the best landfill sustainability.

- Texas and other southwestern states have a relatively large landfill capacity.

- Vermont, Rhode Island, Massachusetts, and the New England region have been identified to experience severe landfill issues and a lack of refuse disposal.

- Blue Ridge LF in Fort Bend County, which has the highest landfill design capacity in Texas, demonstrates a strong commitment to sustainability when the large amount of waste in place (tons) is also factored in.

## References

- Cohen, B. (2023). Lecture on Leaflet - Harrisburg University of Science and Technology

- Leaflet for R. (n.d.). Retrieved May 1, 2023, from https://rstudio.github.io/leaflet/basemaps.html

- The data are available from the Environmental Protection Agency (EPA). Retrieved April 26, 2023. https://www.epa.gov/lmop/landfill-technical-data. link named “Landfill-level data only.

- Mercer County. (n.d.). State FIPS Code Listing. Retrieved April 26, 2023, from https://www.mercercountypa.gov/dps/state_fips_code_listing.htm

- U.S. Census Bureau. (2023). US Shape Files. Retrieved April 29, 2023, from https://www.census.gov/geographies/mapping-files/2021/geo/carto-boundary-file.html

- Legend and color of polygons in R from https://stackoverflow.com/questions/56659000/the-legend-colors-are-not-perfectly-similar-to-color-of-polygons
