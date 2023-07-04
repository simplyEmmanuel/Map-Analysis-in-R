# Landfill Methane Outreach Program (LMOP)

## Introduction
"The LMOP Landfill and Landfill Gas Energy Project Database (LMOP Database) contains information such as physical address, latitude and longitude, owner/operator organization, operational status, year opened, actual or expected closure year, design capacity, amount of waste in place, gas collection system status and landfill gas (LFG) collected amount for 2,637 municipal solid waste landfills. For landfills that report under EPA’s Greenhouse Gas Reporting Program (GHGRP), LMOP cross-references that data set by including GHGRP’s 7-digit Facility Identifier." - LMOP

Reference: https://www.epa.gov/lmop

## Aim: The main goal of this research is to utilize the map to analyze locations and characteristics of landfills in the United States.

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

