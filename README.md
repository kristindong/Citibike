# bikesharing

## Overview

Following the success of New York City's Citibike program, we want to evaluate if a similar bikesharing program can be successful in another city by analyzing Citibike's usage data. For this analysis, we looked at August 2019 trip data, which includes trip durations, start and stop locations, start and stop times, and basic user demographic information.

## Results

For the month of August 2019, there were over 2.3 million trips totaling more than 680,000 hours of usage. The average trip lasted 17.5 minutes. The majority of trips were taken by subscribers, more trips were taken by males than females, and the majority of trips were made by riders born between 1980 and 2000.

![Basic_Data](Basic_Data.png)

Most trip durations are under 30 minutes, with the mode at 5 minutes and very fews trips lasting more than one hour.

![Checkout_Times_for_Users](Checkout_Times_for_Users.png)


Trip duration by gender is similar to trip duration for all users. The mode is six minutes for female and 5 minutes for male.

![Checkout_Times_by_Gender](Checkout_Times_by_Gender.png)


The heatmap below shows usage by day of week and time of day. Usage is highest between 8AM to 9AM and between 5PM and 7PM from Monday to Friday, with lighter usage on Wednesday and Friday, and highest usage on Thursday. Usage on the weekend is more evenly spread out throughout the day. 

![Trips_by_Workday](Trips_by_Workday.png)


The usage pattern described above is similar when broken down by gender.

![Trips_by_Gender](Trips_by_Gender.png)


For male subscribers, peak usage is on Thursday and lowest usage is on Sunday. This pattern is similar but less prominent for female subscribers. Usage is highest on weekends for all non-subscribing customers regardless of gender.

![Trips_by_User_Type](Trips_by_User_Type.png)



## Summary 

Based on the dataset, Citibike usage appears to be predominantely driven by male subscribers. Most trips are short, lasting 17.5 minutes on average, and rarely extend beyond one hour. During the workweek, usage is heaviest during morning and evening commute hours, while weekend usage is more evenly spread out throughout the day. Usage by day and hour patterns appear to be consistent across genders, although female usage is much lower than male.

For further insight, the following analysis and visualization are recommended:
1. Average trip duration by day of week and start hour, and segment the analysis by user type
2. Determine what proportion of trips start and end at the same location vs. those that end at a different location, and segment the analysis by gender and/or user type
