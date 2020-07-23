![NYU Center for Urban Science and Progress](http://github.com/angelialau/CUSP_WatershedInvestments/assets/nyu-cusp-logo.png)
![NYC Department of Environmental Protection](http://github.com/angelialau/CUSP_WatershedInvestments/assets/NYCLogo.png)
# CUSP Watershed Investments
This repository contains the notebooks which were utilized for exploratory data analysis in the 2020 CUSP Capstone project: Economic Impacts of New York City’s Investment in Water Supply.

For data confidentiality reasons, the data files have not been included.

## Description
NYC Department of Environmental Protection (DEP) is interested in understanding the economic impacts of source water protection. This project develops an interactive, web-based visualization tool for exploring trends in and relationships between DEP’s Land Acquisition Program and economic metrics including annual Real Average Salary, Average Employment and number of Establishments in NYC’s watersheds.

<em>This repository is created in fulfillment for NYU CUSP capstone program 2020 requirements. </em>

## Team
Asnat Ghebremedhin <strong>(ag6917)</strong>, Angelia Lau <strong>(al6481)</strong>, Ross Alexander MacWhinney <strong>(ram844)</strong>, Pratik Prakash Watwani <strong>(ppw220)</strong>

Mentor: Prof. Huy T. Vo

# Description of Notebooks
1. QCEW: Exploration and data export of Quaterly Census of Employment and Wage data
1. Lands: Exploration of  Land Acquisition Program data from DEP
1. Corr_QCEW_LAP: Computation of correlation values between annual QCEW metrics and annual LAP acreage per counties
1. agri_annual_data: Exploration of US Department of Agriculture annual yield per acre data for West Of Hudson (WOH) counties
1. agri_census_data: Exploration of US Department of Agriculture 5-yr agriculture census data for West Of Hudson (WOH) counties
1. LULC_LAP_EDA: Exploration of WOH specific LAP data that has been spatially joined with Land Use data given by DEP, aggregation of land use types
1. Corr_QCEW_LULC_LAP: Computation of correlation values between WOH counties and LAP acreage for each land use
1. Occupation_Analysis: Exploration of NYS and WOH employment and industry trends in the years 2000-2018

# Requirements
* Python 3
  * numpy
  * pandas
  * geopandas
  * matplotlib
  * seaborn

## Directory Structure

    ├── README.md
    ├── data
    ├── notebooks
    ├── output
    ├── figures
        └── QCEW_2000-2018
        
## Project websites
Link to the project website: [NYC DEP Watershed Investments](https://pratikwatwani.github.io/cuspcapstone/)
Link to the project report: [NYC DEP Watershed Investments - Report](https://app.gitbook.com/@pratik-watwani/s/economic-impacts-of-new-york-city-s-investment-in-/)
