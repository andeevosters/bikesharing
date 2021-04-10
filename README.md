# bikesharing

## Overview
We are helping a client with a pitch to investors that a bike-sharing program in Des Moines is a solid business proposal. Specifically, one of the key stakeholders asked for a bike trip analysis using the NYC citibike data. He wanted to see the following:
* The length of time that bikes are checked out for all riders and genders
* The number of bike trips for all riders and genders for each hour of each day of the week
* The number of bike trips for each type of user and gender for each day of the week.

In order to truly understand the implications of the answers to questions posed, it's important to learn the full story the data tells. We'll uncover that here, with focus on riders by gender and customer types.

## Results

### 1. The popularity of the various starting points in NYC
The variance in popularity is 1 bike at a starting point up to 16,564 bikes, and this is shown by the size of the circles. 
To little surprise, the outlying neighborhoods "launch" less bikers, while the heart of downtown, areas popular with tourists, for example, boast the highest number of starting points.
![Popularity of Starting Points in NYC](https://github.com/andeevosters/bikesharing/blob/main/Images/starting_point_popularity.png)

### 2. Which day of the week and which time of the day is most common to ride 
This heat map shows ride traffic volume by days of the week and hours of the day. The heaviest traffic is around 7-9am and again from 5-6pm. There is also a somewhat volume increase over the weekend, which might imply tourists. The heaviest traffic points to the suggestion that riders use bikes as a method of travel to and from work (upwards of 45,000 riders at one time).
![Popular Days & Times of Day to Ride](https://github.com/andeevosters/bikesharing/blob/main/Images/day_time_ride_heatmap.png)

### 3. The distribution of riders by rider type: customer vs. subscriber
Subscribers account for an overwhelming 81% of all riders. This suggests that tourism isn't a large reason for the number of riders, as tourists wouldn't likely be incentivized to subscribe; rather, that would likely be locals who work 8-5 (see previous visual).
![Subscriber vs. Customer Ratio](https://github.com/andeevosters/bikesharing/blob/main/Images/subscriber_v_customer.png)

### 4. The distribution of riders by gender  
Male riders account for 72% of all riders who shared their gender (65% of all respondents). While the data doesn't tell us why, one question of interest to answer next would be if females have safety concerns (ex. traveling alone).
![Gender Ratio](https://github.com/andeevosters/bikesharing/blob/main/Images/gender.png)

### 5. The length of time that bikes are checked out for all riders and genders
Most rides last less than 8 minutes. Males ride for 5 minutes on average, and females for 7 minutes.This might imply that bikes are not used as much for recreational purposes as much as for logistical purposes.
![Trip Duration by Gender](https://github.com/andeevosters/bikesharing/blob/main/Images/duration_by_gender.png)

### 6. The number of bike trips for each type of user and gender for each day of the week
Female subscribers and transactional customers generally ride evenly every day of the week. Male subscribers, however, account for most rides, with the majority of rides occurring during the week (heaviest traffic on Thursdays). Note: the least common day for a male subscriber is still more dense than female subscribers or all transactional customers on their busiest days.
![Weekday Ride Heatmap: Customers vs. Subscribers](https://github.com/andeevosters/bikesharing/blob/main/Images/Weekday_ride_heatmap.png)

### 7. The number of bike trips for all riders and genders for each hour of each day of the week 
The results on this heat map mimic the heat map in #2, showing that there is no real difference in riding time preference between genders.
![Heatmap of Popular Ride Times by Gender(A)](https://github.com/andeevosters/bikesharing/blob/main/Images/heatmap_by_gender2.png)
![Heatmap of Popular Ride Times by Gender(B)](https://github.com/andeevosters/bikesharing/blob/main/Images/heatmap_by_gender1.png)


## Summary
Bikesharing is an extremely popular method of transportation in NYC, which makes sense in that access to owning and driving a car is minimal in NYC. The data really points to three primary takeaways: bikesharing is especially popular among males, they are subscribers, and they use the bikes during traditional, high-traffic work hours.

With further analysis of the existing data, you'd benefit from looking at at least two more datasets to help make your decision on feasibility.
* How many miles are put on each bike in a year, to help determine maintenance costs
* Location of riders by gender and age, to help determine who to target in advertising in your potential venture.


For further review, please review the Tableau data itself.
[link to dashboard](https://public.tableau.com/profile/andrea.d.vosters#!/vizhome/BikesharingStory_16175149998000/Story1?publish=yes)
