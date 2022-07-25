# (Ford GoBike System Data Exploration)
## by (Faith Ugwu)


## Dataset

> The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February, 2019. The original dataset has 183412 rows and 16 columns; after wrangling, the dataset has 174952 rows and 20 columns.
I performed the following wrangling steps for better analysis: conversion of the duration_sec column to minutes, spliting the start time column into date, day, and hour, thereby adding new columns for duration in minutes, start date in yyyy-mm-dd format, start hour of the day, and day of week. I also changed the inaccurate datatype in affected columns.
> The original dataset is available in [Udacity Classroom](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)

## Summary of Findings

> In the exploration, my main variable of interest is duration, which helped me to see the amount of time riders spend on each trip and the factors that influence this duration. The majority of rides lasted between 8 - 12 minutes and this took place during work days (Mon - Fri) between 7am and 7pm. Most riders were male subscribers who did not use bike share for all trip. Customers rode bikes for a longer duration compared to subscribers, and female customer bikers have the longest average duration of bike trips across the week days. Bike trips taken during the weekend were the longest.

## Key Insights for Presentation

> For the presentation, I concentrated solely on bike usage based on duration, user type, gender, start hour, and day. I began by introducing the duration min variable, demonstrating how most rides lasted 8 to 12 minutes using a histogram plot on a log transformed scale. Then I demonstrated how this duration varies by gender, user type, start hour, and days. I also demonstrated how bikes were used based on these features.