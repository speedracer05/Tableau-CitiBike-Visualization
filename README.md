# Tableau CitiBike Analytics
## University of California Davis Data Analytics and Visualization Boot Camp 2021

<p align="center">
<img src="Images/citi-bike-station-bikes.jpg" width="720">
</p>

This report provides a summary of Citi Bike usage in Jersey City, NJ for the first quarter of 2021. The data source utilized for this project was from [Citibike](https://www.citibikenyc.com/system-data). The objective is to aggregate data from Jersey City, Citi Bike Trip History Logs and design a visualization for each discovered phenomena.

## Table of Contents
-   [How to View](#how-to-view)
-   [ETL Data Preparation](#etl-data-preparation)
-   [Research Questions](#research-questions)
-   [Analysis](#analysis)
-   [Tools and Other References](tools-and-other-references)
-   [Credits, tools and other references](#credits-tools-and-other-references)

## How to View
1. [Data Source](https://www.citibikenyc.com/system-data)
2. Go to this link to see my [Tableau Public Workbook](https://public.tableau.com/app/profile/john7267/viz/CitiBikeAnalysisJerseyCityQ12021v2/Story1?publish=yes)
3. In the lower, right corner of the slide is the "Full Screen" mode - click it.
![tableau slide](https://github.com/speedracer05/...)

## ETL Data Preparation
- Extracted data from Citi Bike System Data for January 2021 - March 2021
- Transformed data in Jupyter Notebook:
 - Split datetime stamp into separate date and columns
 - Renamed columns
 - dropped Nan rows, empty cells, and unneccessary columns
 - merged dataframes
 - calcuated trip distances, point a to b, using latitude and longitude, converting degrees to radians, approximating the earth radius and subtracting the difference to come up with miles
 - Exported data into a csv file
- Loaded dataset into a Tableau workbook

## Research Questions
1. What is the aggregate total number of trips recorded in Q1?
2. What is the aggregate miles recorded for all stations?
3. What bike stations recorded the most trips and miles.
4. Top 10 stations with highest traffic
5. Top 10 stations with lowest traffic
6. What is the useage pattern in Q1?
7. Which station recorded the most traffice and mileage?


## Analysis
The analysis is divided into four sections; Station Popularity, Station Drill Down, Bike Useage, Top Station Performance.

#### Station Utilization
There are over 50 Citi Bike Stations, in Jersey City. Collectively there were over 29K trips recorded in the first the 3-months of the year, and over 8,000 miles. 

#### Station Drill Down
Of over 50 stations, six Citi Bike Stations, Grove St PATH, Sip Ave, Hamilton Park, Newport Pkwy, Newport PATH, and Marin Light Rail (MLR), originated over 1,000 trips in Q1. 
- The same six accounted for 39% of all recorded rides.
- The most popular start bike station is Grove St PATH and Sip Ave 
- The highest utilized ride segments to start/end are between rail stations, with MLR to Grove St and Grove St to MLR 

#### Bike Useage
It was surprising to find that there were a number of riders using Citi Bike in the winter months of January and February. 
- Usage increased over 400% from, February to March, as the weather warmed 40 degrees to 68 degrees respectively.
- The average distance traveled from the start to end station is .56 miles. 

#### Top Station Performance
Grover St PATH is the most popular starting station, as demonstrated by the number of riders starting their transit. In fact, the number of riders at the station is 75% greater than the next busiest station at Sip Ave.

This makes sense since it is the terminal station for several public rail lines 


## Tools and Other References
- Jupyter Notebook

```bash
import pandas as pd
```

