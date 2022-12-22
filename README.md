# Surfs_Up

## Overview
The client, W. Avy, would like to open a surf shop in Oahu, Hawaii. Before moving forward with the plan, he wants me to perform an analysis on the temperature data in the area in order to make sure that the shop can be opened all year. In order to achieve this, data frames will be created of the temperature statistics in the months of June and December from the past several years. This will be done using Python, Pandas, and SQLAlchemy.

## Results
Below you will see the two charts showing the temperature statistics for June and December.

<img width="193" alt="Screen Shot 2022-12-22 at 12 29 31 AM" src="https://user-images.githubusercontent.com/43667985/209063992-09c11a83-5f45-41bc-bdda-c016f051032b.png"> <img width="225" alt="Screen Shot 2022-12-22 at 12 29 46 AM" src="https://user-images.githubusercontent.com/43667985/209063997-b137bbbf-24a3-46f8-aaaf-b335da38da4e.png">

#### There are some key differences between the data points for the two months:
- June has 183 more data points than December (1700 to 1517). This will cause the June data to be more accurate when analyzing the temperature statistics for that month.
- The mean temperatures are only seperated by about 3.9 degress (74.9 to 71). This is promising information for the client as customers will be encouraged to visit the store throughout the year as the temperature will be comfortable for most people to be outside.
- While the max temperatures are different by only 2 degrees (85 to 83), the minimum temperatures are different by 8 degrees (64 to 56). The client will have to factor this data in his decision for the winter months and make sure the store is well equipped and comfortable for customers when the temperature drops below 60 degrees.

## Summary
The temperature data for June and December over the past several years is very similar which makes the idea of keeping a store open year-round very appealing. The mean temperature is above 70 degrees for both months which means that the majority of people will have no problem being comfortable outside and checking out the store.

In order for the client to make more informative decisions on the weather conditions of Oahu, he could gather more information that could be extracted using queries. The dataset contains the amount of rainfall for each data point. This could be helpful in determing when there is more rainfall during the year and if it would be a factor when deciding to open the store year-round. Another query that could be created is comparing the temperature for each month to the respective rainfall amounts. A histogram could plot the data and determine if there is a relationship between the temperature and how much rainfall there is throughout the year.
