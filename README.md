# Module 9 Challenge

## Challenge Overview
The purpose of this analysis is to analyze the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.



## Resources
- Data source: hawaii.sqlite
- Software/Libraries: SQL Lite Database, numpy, pandas, datetime, sqlalchemy

## Challenge Results
For the Temperatures of June, we have the following results:
count: 1700.000000
mean: 74.944118
stdev: 3.257417
min value: 64.000000
25th percentile: 73.000000
50th percentile: 75.000000
75th percentile: 77.000000
max value: 85.000000

For the Temperature of December, we have the following results:
count: 1517.000000
mean: 71.041529
stdev: 3.745920
min value: 56.000000
25th percentile: 69.000000
50th percentile: 71.000000
75th percentile: 74.000000
max value: 83.000000

## Challenge Summary
To summarize the result, for the month of June, the temperature ranges from 64 degrees to 85 degrees, with the average of 74.94 degrees, it is definitely desirable temperature for surfing. Regarding ice cream business, it is clear that ice cream will be desirable in this weather as well so we can conclude that June is a good month for surfing and ice cream business. Regarding the month of December, the temperature ranges from 56 degrees to 83 degrees with the mean of 71.04 degrees. While the mean temperature compare to June is not significantly lower, the minimum temperature is significantly lower than the minimum of June (8 degrees). Therefore, we can conclude that there will be days that surfing and ice cream will not be desirable as it is quite cold of the temperature goes below 60 degrees. 

To further our understanding regarding low temperature days in December, we need to do a query of the number of days that the temperature is below 60 degrees in December to see how many days the temperature makes surfing and ice cream undesirable. Similarly, we can also run an additional query on number of days where temperature is higher than 75 degrees in June to see how many days surfing and ice cream will be most desirable. 