<<<<<<< HEAD
# Tableau CitiBike Analytics

-   [About](#about)
-   [How to View](#how-to-view)
-   [ETL Data Preparation](#etl-data-preparation)
-   [Analysis](#analysis)
-   [Installation and Usage](#installation-and-usage)
-   [Credits, tools and other references](#credits-tools-and-other-references)

## About
Citi Bike usage in Jersey City, NJ for Q1 2021. This report is a summary of of bike usage in the first quarter of 2021, using data provided by [Citibike](https://www.citibikenyc.com/system-data). The objective is to aggregate the data from Jersey City Citi Bike Trip History Logs and design a visualization for each discovered phenomena.


### 

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
There are over 50 Citi Bike Stations, in Jersey City, that recorded over 29K trips, and over 8,000 miles, in the first 3-months of the year.

#### Station Drill Down
Of over 50 stations, six Citi Bike Stations originated over 1,000 trips in Q1. The same six accounted for 39% of all recorded rides.

#### Bike Useage
It was surprising to find that there were a number of riders using Citi Bike in the winter months of January and February. Useage increased, as the wather warmed from a January average of 34 degrees to 65 degrees in March

#### Top Station Performance
Grover St PATH is the most popular starting station, as demonstrated by the number of riders starting their transit. In fact, the number of riders at the station is 75% greater than the next busiest station at Sip Ave.

This makes sense since it is the terminal station for several public rail lines 

## Installation and Usage

## Tools and Other References
- Jupyter Notebook

```bash
import pandas as pd
```
=======
# Tableau CitiBike Analysis

-   [Table of contents](#table-of-contents)
-   [About](#about)
-   [How to View](#how-to-view)
-   [Data Preparation](#data-preparation)
-   [Observations](#observations)
-   [Installation and Usage](#installation-and-usage)
-   [Credits, tools and other references](#credits-tools-and-other-references)

## About
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin at quam et orci
ultricies ornare. Fusce nec magna aliquet, congue ante in, lobortis augue. Nunc
hendrerit massa ut risus molestie egestas.


### 

## How to View
1. [Data Source](https://www.citibikenyc.com/system-data)
2. Go to this link to see my [Tableau Public Workbook](https://public.tableau.com/profile/...)
3. In the lower, right corner of the slide is the "Full Screen" mode - click it.
![tableau slide](https://github.com/speedracer05/...)

## Data Preparation
- Extracted data from CitiBike
- Transformed data in Jupyter Notebook
..* Exported data into a csv file
- Loaded dataset into a Tableau workbook

## Research Questions
1. Top 10 stations for starting a ride (compare subscription vs casual riders)
2. Top 10 stations for terminating a ride
3. Ratio of Subscribers vs Casual customers
4. Top 3 stations with highest traffic
5. Top 3 stations with lowest traffic
6. Number of under utilized stations
7. Total number of trips
8. Growth rate month to month
9. Growth qtr over qtr (Jan-Mar '20 vs '21)


## Observations

## Installation and Usage

## Credits, Tools and Other References

```bash
import pandas as pd
```
>>>>>>> 8f7de7f121dae0bbd0aaa3fc4445ab3f72d3308c
