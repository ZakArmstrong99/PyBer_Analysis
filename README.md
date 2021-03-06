# PyBer_Analysis

## Overview of the analysis:
The purpose of this analysis is to find and visualize the weekly PyBer fares for each city type (Rural, Suburban, and Urban). This was done by using the city_data.csv and ride_data.csv, which contains all the needed data to complete the analysis. The pandas library and matplotlib library provide the tools to organize the data correctly and to create a plot which displays the data. Using this information, it is possible to analyze the differences between the weekly fare costs between city types. The analysis made on the plot and data can help PyBer make changes to help business.

## Results:
The first part of the analysis was to create a summary which included information on the different city types. The data in the chart includes the total rides, total drivers, total fares, average fare per ride, and average fare per driver.

![pyber_summary](https://user-images.githubusercontent.com/107213807/178583611-9301269e-4413-4343-842f-ab1b46b34e2a.png)

Looking at this dataframe, we can see that Urban has the highest number of total rides by far with 1,625. Not only that, the urban city type has the highest amount of total fares while also having the lowest average fare per ride and per driver. This makes sense as urban areas have more demand for ridesharing services due to higher concentrated population and less access to parking. This is evident as the values for the totals are lower in respect to the population of city type (Urban being the highest and rural being lowest).

The next data frame displays the weekly fares for each city type between 01/06/2019 to 04/28/2019. This dataframe is crucial to the goals of the analysis as it provides the data needed to visualize the weekly fares for each city on a line plot.

![total_fare_city_type_chart](https://user-images.githubusercontent.com/107213807/178587135-46791828-a0e8-41ff-af45-e47c7c076973.png)

Looking at the chart, we can see that this data frame follows a similar trend to the last, with the urban city type having the highest weekly fare and rural having the lowest. With this data we then plot it to make it easier to visualize.

![total_fare_city_type](https://user-images.githubusercontent.com/107213807/178594515-12680815-7644-4d57-b003-9e3038ef0146.png)

When looking at the chart initially, all three city types follow similar trends over the weeks. The three city types all spike the last week of february, while declining the first week of March. The last week of February was the peak for urban and suburban, while the peak for rural was the first week of April.

## Summary:
After looking at the results, there are some recommendations that address the disparities of the city types. When looking at the PyBer summary, the difference between total drivers is quite big, especially for rural areas. One way to possibly increase the weekly fares for rural cities is to implement some type of incentive for drivers to work in rural city types. This could increase the total amount of rides in a week, leading to less disparity among the city types. This would also increase the total fares for rural cities, which are much lower than the other city types. Another recommendation that would increase total fares for urban city types would be to increase the cost per fare after a high total fare week. When looking at the graph, the end of February and beginning of March have two high points, but the week after the total fares drop. Increasing the fare cost per after a relatively high total fare week could reduce the change of total sales per week and be more stable. The last recommendation would be to slightly decrease the total number of drivers in suburban city types. This would increase the total fares as rides would become more valuable. Suburban city types aren't as large as urban ones so I don't believe it would lower the total number of rides. The key for this to work would be to make sure to find balance between the average fare per driver and total drivers.


