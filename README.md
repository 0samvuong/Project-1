# Project-1 


# Update
We can’t put all our required columns into 1 Dataframe.

Our main DataFrame should only have 1 row for each accident – we get this from the ACCIDENT DataFrame, ACCIDENT_NO column.

For the other dataframes (node/weather/person/etc.), they most likely have multiple ACCIDENT_NO’s (which means multiple rows for 1 accident). If we try to merge those rows into the main DataFrame, we will get multiple rows for each accident (sort of), and that will ruin our main DataFrame. 

##What to do now?
1)	Load all CSV files as its own DataFrame (I’ve done that already, mostly.)
•	There should have around 10 
2)	Select the last 5 years of accidents (2015-2020), and put that in the Main DataFrame
•	We now have the ACCIDENT_NO of all accidents in the last 5 years
3)	For all other DataFrames, make sure that they only contain rows that have the same ACCIDENT_NO as the main DataFrame
•	Now all the DataFrames only have data for accidents for the last 5 years.



## Project Proposal - 

Merge test please ingore

We are looking to find the relationship between road accidents and time,age,gender,road condition,speed,cause of accident, location,DUI,

We are analysing victorian crash statistics. 


## Scope:
Date: 2015-2020


## Group Members:

Mohammed Nasser
Hannah Qu
Phuong Tieu
Sam Vuong

### Resources:

### Vicroads overview (datasource + interactive analysis):
https://www.vicroads.vic.gov.au/safety-and-road-rules/safety-statistics/crash-statistics


### Source of Dataset (Crash Stats link)
https://discover.data.vic.gov.au/dataset/crash-stats-data-extract


### Metadata (column description)

https://data.vicroads.vic.gov.au/Metadata/Crash%20Stats%20-%20Data%20Extract%20-%20Open%20Data.html
