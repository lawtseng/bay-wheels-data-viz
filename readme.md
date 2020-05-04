# Diamonds Data Exploration

## Dataset

Bay Wheels (previously Ford GoBike) is a bike sharing system in the San Francisco Bay Area, which provides its users different options to use the bike including monthly membership, annual membership, affordable program for qualifying residents, single pass, and daily pass. The dataset we use in this project consists of the information about 258,000 trips of Bay Wheels bike system in July, 2019. The data includes duration time, start/end time, start/end station location and ID, bike's ID, and some subscription's information. The Bay Wheel's trip data as well as its pricing information can be found [here](https://www.lyft.com/bikes/bay-wheels/system-data).


## Summary of Findings

In the exploration, we found that the majority of Bay Wheels's users are commuters who use the bike system as their main transportation mode or as the mode for the last-mile travel between bus/train station and the office. This conclusion stems from the findings listed below:
1. The number of trips on weekdays is generally higher than weekends.
2. The number of trips varies hugely on weekdays, which peaks during peak hours, from 8 am to 10 am and from 5 pm to 7 pm.
3. While the number of trips during morning and afternoon peak hours are high, the duration time (min) in these hours are shorter than other time of the day.
4. The majority of bike trips are contributed by *subscribers*, who buy membership and tend to use more frequently, than one-time *customers*.
5. The average duration time of *subscribers* is 12 minutes on weekdays, which is about half the time of *customers*.
6. The amount of trips by *customers* does not change much throughout the day; therefore, the main contributing factor of the distribution of trips in one day is *subscribers*.

Interestingly, the duration time of *subscribers* on weekends remain short, using approximately 14 minutes in average, while the pattern of the number of trips change a lot.

## Key Insights for Presentation

The presentation will focus on the influence of user types, time of the day, and day of the week. It starts by introducing the goal of the investigation and the information of the dataset utilized in this project. After that, we discuss the distribution of duration time and plot it by log scale.

Afterwards, we investigate how the usage rate and duration time change by user types, by different hours, and by different days separately. All of these comparisons are shown in bar plots. More complicated plots are created to show the relationships between the major variables of duration time, user types, hours of the day, and days of the week with heat map and grid plots.
