# Data Exploration with Ford GoBike Datassss

## Project Table of Contents:
* Introduction
* Preliminary Wrangling
* Univariate Exploration
* Bivariate Exploration
* Multivariate Exploration
* Summary
* Sources

Data source: https://www.fordgobike.com/system-data <br>
The data consisted of bike station and user information of about 160,000 records. The features includes as below, 
* ride_id
* rideable_type
* started_at
* ended_at
* start_station_name
* start_station_id
* end_station_name
* end_station_id
* start_lat
* start_lng
* end_lat
* end_lng
* member_casual

Due to create the correct data visualization, I did the data cleaning and transfer some of the features to the right data type. Also, I create some columns such as duration for having the further insight.

## Questions to be answered:
1. How the weekday usage looks like
2. How the hours usage looks like
3. How long the people take to ride the bike
4. What is the distance the people ride the bike
5. What is the most popular start station and end station
6. What is the user type looks like? (Casual users V.S Member users)
7. Compare the distance between two different user types
8. Compare the duration between two different user types


## Summary of Findings

During the exploration, I found that Saturday has the most numbers of bike trips, and the highest number of users use the system around 5 pm. Most of the users ride the bike for the short distance which is less than 2 km. Market Station at 10th Street is the most popular station for start point and end point.

Moreover, there are more casual users using this system than member users. And the average distance for casual users is larger than member users. And I also found that Saturday has the most user number for casual users and Tuesday has the most user number for member users. I also dig into the rideable type and found that docked bike is more popular than electric bike.

I tried to get more insight through multivariate exploration. I found that during weekdays, most number of casual users use the system between 4-6pm and most bike rides occur between 12am and 14pm during the weekend. However, most number of member users use the system between 4-6pm during the weekdays but there is a significant drop in the number oft rented bike during the weekend. 





