# Pyber Analysis of Fares

# Overview and Scope
The purpose of this study was to determine the impact of fare revenue by type of city in existing markets.  Specifically, the study needs to show how revenue changes by type of geographic grouping: Urban, Suburban, Rural.  

# Approach
The analytical approach used was to collect data by city and ride types and then merge it into a single dataframe for analysis.  The specific data collected and used for analysis was:
- City name
- City type or classification(Urban, Suburban, Rural)
- Number of drivers in the city
- Date of fare or ride
- Fare amount
To accomplish the analysis and develop recommendations, the data was summarized to:
- Total Number of Drivers by city type
- Total Fare Revenue by city type
- Average fare or revenue per ride
- Average fare per driver

The time frame of the analysis is year-to-date through April of 2019.  The sample size of data is relatively small and the ability to review data from a full year cycle would possibly provide more insight.  There could be seasonal patterns that change ride volumes in different city types.

# Results

The results of the analysis are summarized in the table below.

<img src="Resources/Table of Fare Drivers.png" alt="Resources/Table of Fare Drivers.png" width="1000" >

A graphical representation of our results is shown below.  The graph segments fare revenue by city type for our analysis time frame, January to April.

<img src="analysis/Pyber Challenge Fare by City Type.png" alt="analysis/Pyber Challenge Fare by City Type.png" width="1000">

# Summary and Recomendations
As we know, our business model and revenue are driven by two factors:
- Population density which drives number of rides or ride frequency
- Geographic location which drives ride distance.

The summary table clearly shows how the volume of rides increase by more than 10x from Urban to Rural areas.  The average revenue per ride is highest in the Rural geographies primarily becuase of travel distance.  Average fare per ride is 41% higher for Rural cities compared to Urban cities.  Total Fares or Revenue is of course highest in Urban areas driven by volume of rides and availability of drivers. The Suburban areas consistently fally in between Rual and Urban in all measures.
Suburan cities have only 38% of the Urban rides but generate slightly less than half as much in total fares.  Consequently, Suburban fares per driver and per ride are measurably better than the Urban cities.  Average fare per ride is about 25% better and fare per driver is about 2.5X the Urban performance.  

Average fare per driver is substantially higher in the Rural cities.  Fare per driver is approximately 3.5x higher for Rural drivers driven by the low number of drivers and distance of rides.  The Urban drivers have a relatively low fare per ride and there is risk of driver turnover due to possible low compensation.  Their market is comprised of mostly shorter rides and if there are too many available drivers they might receive fewer rides.

## Conclusions
Total fares or revenue will continue to be heavily driven by the Urban cities due to volume of demand for rides.  Suburban cities have excellent driver productivity and if they are outlying areas of Urban centers then can provide good expansion and revenue sources.

Recommendations for the CEO are as follows:
## Additional Analysis
In order to better understand the market the following analysis should be initiated:
- Determine the revenue or fare per ride mile by city type
- Number of rides per day by driver by city type
- Expand the data time frame or horizon - minimum of one year 

## Revenue Growth
- Continue to expand primarily in Urban cities with secondary consideration to Suburban cities.
- Limit Rural growth to areas that are geographic extensions of existing Urban or Suburban servied cities.

##  Managing the Revenue Stream
- Establish key performance indicators by geography and driver group for both quantity of rides and quality of service.
- Build dashboards to track KPIs
- Establish weekly and monthly reviews.  
  - Weekly reviews should have a tactical focus and include any corrective aciton based on variations from expected outcomes.
  - Monthly reviews should be more strategic and look at the larger trends in the markets and expansion plans

