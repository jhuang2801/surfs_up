# surfs_up
## 1. Overview of the analysis: Explain the purpose of this analysis.
Using Pandas and SQL Alchemy, the hawaii.sqlite database was extracted for all the temperature for the month of June and December. After temperature values were retrieved from each month, the values were converted into lists (for June and December, respectively) to display temperature trends corresponding to each month.

## 2. Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
1. The temperature range was given for both months. For June, the minimum temperature point is 64 degrees with the maximum temperature point at 85 degrees. For December, temperature range is ranging from 56 degrees as the minimum to 83 degrees as the maxium temperature.
2. There are more temperature points collected for June (count: 1700) vs Dec (count: 1517) even though December has more days than June.
3. The average temperature in June is at 74.94 (with standard deviation 3.25), and the average temperature in December is at 71.04 (with standard deviation 3.75). 

## 3. Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
There is no significant difference for the temperature data in June vs in December. The average temperature points are very similar: 74.94 degrees in June vs 71.04 degrees in December. The variation of the two become more visible when the temperature ranges are considered as a whole - while the maximum temperature in the two months are very similar (85 deg in June vs 83 deg in December), the lowest temperature in December is almost 10 degrees lower than the lowest temprature in June (56 deg in December vs 64 deg in June).
 Since there are more data points collected in June than December, the number of temperature point collected per day is not known based on data analysis thus far. A line graph can be used to show temperature trend for each month, such as fluctuation within a day, day to day comparison, or even weekly forecast. 

