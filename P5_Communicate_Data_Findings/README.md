# Bay Wheel Trip Data Analysis January 2020

Sercan Noyan Germiyanoğlu

March-2020

## Dataset

The data consist of approximately 300K bike rides from January 2020 dataset. The attributes include the duration in seconds start station/end station information as well as additional information such as user type, bike share for all trip and lastly rental access method. 300K data points were removed from the analysis due to date format of start/end time to learn which day users start to ride a bike, which hours users start to ride a bike and end their trip. The dataset add some new variables whose name duration in minutes converting its seconds to minutes and distance in km calculating distance between the location of start station and end station.The data can be found [here](https://s3.amazonaws.com/fordgobike-data/index.html), with feature documentation available [here](https://www.fordgobike.com/system-data).


## Summary of Findings

In the exploration, there are findings to be itemized as each step shown below.

### Univariate Exploration

<b>Visualization 1</b> - The last three days of Janurary as 28th,29th and lastly 30th are shown the most usage of bay wheels.

Visualization 2 - The trip duration in minutes for all number of bike bikes is ranged from 0 - 60 minutes.While most people use the bay wheel system to ride a bike in approximately 0 - 10 minutes, not too much people have been riding a bike for more than 10 minutes.The figure is right-skewed graph because most variable are located left-hand side.

Visualization 3 - While the number of subcribers are extended from 16000, Customer are consisted of just above 12000. Subcribers are more effective to use the bay wheel system rather than customers.

Visualization 4 - The distance in km for all number of bike bikes is ranged from 0 - 10 km.While most people use the bay wheel system to ride a bike in approximately 0 - 2 km, not too much people have been riding a bike for more than 2 km.The figure is right-skewed graph because most variable are located left-hand side.

Visualization 5 - Most people prefer to ride a bike from Market St at 10th St as the most-preferable starting point.

Visualization 6 - Most people would rather end to ride a bike at San Francisco Caltrain(Townsend St at 4th St) as a most-preferable ending point.

### Bivariate Exploration

Visualization 1 - While the number of customers exceeds the number of subscribers for the usage of riding a bike in some days of January, vice-versa in other days of January. However, when looking the general trend of the number of rides per user type , the number of subcribers are more than the number of customers.

Visualization 2 - The trip duration in minutes of both customer and subcribers for bay wheels system are ranged from 0 - 60 minutes.According to both customer and subcriber, while most people use the bay wheel system to ride a bike in approximately 0 - 10 minutes, not too much people have been riding a bike for more than 10 minutes.When looking the number of bike trips for bay wheels system in both figures, the number of bike trips for bay wheels system in Customer is less than Subscriber's numbers.All thes two figures are right-skewed graph because most variable of each figure are located left-hand side.

Visualization 3 - The distance in km of both customer and subcribers for bay wheels system are ranged from 0 - 10 km.According to both customer and subcriber, while most people use the bay wheel system to ride a bike in approximately 0 - 2 km, not too much people have been riding a bike for more than 2 km.When looking the number of bike trips for bay wheels system in both figures, the number of bike trips for bay wheels system in Customer is little less than Subscriber's numbers.All thes two figures are right-skewed graph because most variable of each figure are located left-hand side.

Visualization 4 - The figure of Customer's weekday usage of Bay Wheels System is affinity with Subcriber's ones except for the number of bike trips. The number of bike trips for Subcriber's weekday usage of Bay Wheels System is more than Customer's one.

### Multivariate Exploration

Visulization 1 - The figure of Customer's hourly usage of Bay Wheels System is little affinity with Subcriber's ones except for the number of bike trips. The number of bike trips for Subcriber's hourly usage of Bay Wheels System is more than Customer's one.For both the figures of Customer and Subcriber, 8pm, 9pm, 16am, 17am and lasty 18am of all weekdays are the most effective time schedule for the usage of bay wheel system.

Visulization 2 - The density of mean trip is low so that both customer and subscribers only just prefer to rent a bide for the usage of their needs and pleasure time with respect to weekday and hour schedule.The highest mean of trip duration is 36.0 at 2.00 am on Tuesday for each week of January.

Visulization 3 - Most trip duration of each day for both Customer and Subscriber is up to 30 minutes becuase the denstity of the trip duration is mostly located at the bottom of plot.

## Key Insights for Presentation

For the presentation, I focus on user types behaviours in January 2020. Since the Bay Wheel System currently is used from Subscribers and Customers, I start by introducing the split between those who use the system occasionally and those who has a membership. Afterwards, I analysis daily and weekly habits of both customers and subsribers in January 2020. I use the heatmap to show when bikes are high in demand throughout the each day of week in January 2020 for both users types. To finish, I introduce the histogram of the mean trip duration by day of Week and Hour, hourly usage of bike system during week and lasty duration of trips in minutes during week for both customer type and subsrciber type.
