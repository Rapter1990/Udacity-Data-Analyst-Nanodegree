# Bay Wheel Trip Data Analysis

Sercan Noyan Germiyanoğlu

March-2020

## Dataset

The data consist of approximately 300K bike rides from January 2020 dataset. The attributes include the duration in seconds start station/end station information as well as additional information such as user type, bike share for all trip and lastly rental access method. 300K data points were removed from the analysis due to date format of start/end time to learn which day users start to ride a bike, which hours users start to ride a bike and end their trip. The dataset add some new variables whose name duration in minutes converting its seconds to minutes and distance in km calculating distance between the location of start station and end station.The data can be found [here](https://s3.amazonaws.com/fordgobike-data/index.html), with feature documentation available [here](https://www.fordgobike.com/system-data).


## Summary of Findings

In the exploration, I found that there are two types of clients using the system: subscribers who are mainly daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and, occasionally around the lunch time, and customers, usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. The bike share system was used more often around summertime (May-October) with a clear drop from January to March, most probably due to the weather condition. Moreover, I have checked if there are some differences in trends for genders. In most cases the trend for males/females was the same, except of the fact that females tend to have slightly longer trips and suprisingly, for casual users there are quite a lot of females using the system between January and March in comparison to males (the ratio is much smaller than for the rest of the year).


## Key Insights for Presentation

For the presentation, I focus on customer habits in 2018. Since the Ford GoBike System currently offers 3 subscribtion types: Single Ride, Access Pass (24h or 72h) and Monthly Membership, I start by introducing the split between those who use the system occasionally and those who has a membership. Afterwards, I move to daily and weekly habits of customers. I use the heatmap to show when bikes are high in demand throughout the week. To finish, I introduce the histogram of the trip duration per customer type to further show the differences in renting behaviour.
