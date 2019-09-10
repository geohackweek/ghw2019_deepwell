# Deepwell

Can we estimate groundwater use with remote sensing data?

## Collaborators:

Anthony Abercrombie: Project Lead

Joel Nicholas: Software Engineering, Data Visualization

Cari Breton: Geology and Economics Domain Expert

Shirley Leung: Water Systems Domain Expert

Rachael ???: Soil Science Domain Expert

Tommy Greene: Remote Sensing, Google Earth Engine Specialist

Chao Chen: Hydrology and Numerical Simulation Domain Expert

## The Problem

Agriculture in California's Central Valley (and other arid agricultural hubs) partially depends on groundwater to irrigate crops. Water consumption that exceeds the rate of aquifer recharge threatens the long term sustainability of agriculture in California. In 2014, the state of California passed the Sustainable Groundwater Management Act (SGMA), which requires governments and water agencies of high and medium priority basins to halt overdraft and bring groundwater basins into balanced levels of pumping and recharge. SGMA is scheduled to be implemented in January of 2021. Local water districts will need to be able to monitor resource extraction and identify incidents of overdraft in order to enforce SGMA and achieve sustainability goals in the next 20 - 40 years. 

The California Department of Water Resources and the USGS share periodic groundwater level measurements at select sites. However, to enforce SGMA, regulators will need to be able to estimate groundwater availability and resource extraction in areas where sensor installation is infeasible (e.g. farmers private property). 

## Application Examples

This project seeks to derive features and indices from a multitude of remote sensing data sources that could power a predictive model for estimating groundwater availability and extraction rate. This could pave the way to an alerting system that identifies point sources of groundwater overdraft.

## Sample data
If you already have some data to explore, briefly describe it here (size, format, how to access).

| Dataset Name                                      | Publisher                          | Link                                                                                                         | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------|------------------------------------|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Periodic Groundwater Level Measurements (CASGEM)* | DWR- Department of Water Resources | https://data.cnra.ca.gov/dataset/periodic-groundwater-level-measurements                                     | Groundwater Levels dataset contains seasonal and long-term groundwater level measurements collected by the Department of Water Resources and cooperating agencies in groundwater basins statewide. It also includes data collected through the CASGEM (California Statewide Groundwater Elevation Monitoring) Program. Most measurements are taken manually twice per year to capture the peak high and low values in groundwater elevations. However, the dataset also includes measurements recorded more frequently, monthly, weekly, or daily.                                                                                    |
| Land Use by Parcel                                | DWR- Department of Water Resources | https://data.cnra.ca.gov/dataset/crop-mapping-2014                                                           | This dataset represents a statewide, comprehensive, field-scale assessment of agricultural land use, as well as urban and managed wetland boundaries for the 2014 year. This data is prepared by Land IQ, LLC and provided to the California Department of Water Resources (DWR) and other resource agencies involved in work and planning efforts across the state for current land use information. This dataset is meant to provide information for resource planning and assessments across multiple agencies and serves as a consistent base layer for a broad array of potential users and multiple end uses. Wolfram candidate |
| USGS Groundwater Levels                           | USGS NWIS                          | https://catalog.data.gov/dataset/usgs-groundwater-data-for-the-nation-national-water-information-system-nwis | USGS National Water Information System (NWIS), which contains extensive water data. Nationwide, the groundwater database consists of more than 850,000 records of wells, springs, test holes, tunnels,drains, and excavations in the United States. Available site descriptive information includes well location information such as latitude and longitude, well depth, and aquifer.                                                                                                                                                                                                                                                |
| CA Bulletin 118 Groundwater Basins*               | DWR- Department of Water Resources | https://data.cnra.ca.gov/dataset/ca-bulletin-118-groundwater-basins                                          | This dataset is a feature class showing the boundaries of 517 groundwater basins and subbasins as defined by the California Department of Water Resources as last modified by the Basin Boundary Emergency Regulation adopted on October 21, 2015. Groundwater basins are represented as polygon features and designated on the basis of geological and hydrological conditions - usually the occurrence of alluvial or unconsolidated deposits. When practical, large basins are also subdivided by political boundaries, as in the Central Valley.                                                                                  |

[More relevant datasets](https://docs.google.com/spreadsheets/d/1NhC1WyYVj2K4N-JpoYQk_7W0ZAbDInjmiYirHUkBaOE/edit?usp=sharing)

## Specific Questions:
TODO

## Existing Methods:
TODO

## Proposed methodss/tools
TODO

## Background Reading
TODO

## Files

* `.gitignore`
<br> Globally ignored files by `git` for the project.
* `environment.yml`
<br> `conda` environment description needed to run this project.
* `README.md`
<br> Description of the project. [Sample](https://geohackweek.github.io/wiki/github_project_management.html#project-guidelines)

## Folders

### `contributors`
Each team member has it's own folder under contributors, where he/she can
work on their contribution. Having a dedicated folder for one-self helps to 
prevent conflicts when merging with master.

### `notebooks`
Notebooks that are considered delivered results for the project should go in
here.

### `scripts`
Helper utilities that are shared with the team

