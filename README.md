# Pyber_Analysis

## Overview of Project

We were tasked to summarize ride sharing data by city type and plot the data weekly over the first four months of 2019. We are going to share our insights with the CEO and provide recommendations for addressing any disparities we find.

See script below:

[PyBer_Challenge.ipynb] (https://github.com/pritchardjeff/PyBer_Analysis/blob/master/PyBer_Challenge.ipynb)


### Results

- Summary Data Frame:
  ![district_summary_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/district_summary_original.png)
 - Summary Chart:
  ![dPyBer_fare_summary] (https://github.com/pritchardjeff/PyBer_Analysis/blob/master/Analysis/PyBer_fare_summary.png)
  
- Impact by city type.
  - Overall, urban cities had the highest volume and lowest rate in each category while rural had the lowest volume but highest rate. Suburban was in between for each category.
  - Below is how each city ranked from highest to lowest in each category:

|Category            | Urban   | Suburban| Rural |
| -------------------|:-------:| -------:| -----:|
| Total Rides        | 1st     | 2nd     | 3rd   | 
| Total Drivers      | 1st     | 2nd     | 3rd   |
| Total Fares        | 1st     | 2nd     | 3rd   |
| Avg Fare per Ride  | 3rd     | 2nd     | 1st   |
| Avg Fare per Driver| 3rd     | 2nd     | 1st   |


### Summary

Three recommendations to the CEO:
- The lower number of rides in suburban and rural areas makes sense due to the implied lower population density in those areas, I would recommend keeping tabs on the demand in those markets to ensure we have good coverage as demand in those areas grow.
- We should look into suburban markets more. On average they bring in 26.3% more revenue per ride than urban rides and brought in half as much in total fares while having a volume at 38% of what urban markets brought in.
- We seem to have more Urban drivers than needed, over our 4-5 month sampled time frame each urban driver had an average of .68 rides. It would make sense to either reduce the number of urban drivers or send them to other areas.



