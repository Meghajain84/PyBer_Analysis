# PyBer_Analysis

## Overview of the analysis: 
Pyber is the python based ride sharing app company. We have been given csv files with driver and ride data in various cities. We need to come up with a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we are required to create multiple-line graph that shows the total weekly fares for each city type. Finally, we will come up with a written report summarizing how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

![summary_dataframe](https://github.com/Meghajain84/PyBer_Analysis/blob/main/Resources/summary_dataframe.PNG)

* We see from summary dataframe image, as we get into busier areas (from rural to suburban, from suburban to urban), number of rides and drivers using pyber app increases, causing average fare per ride and average fare per driver to decrease. The disparity is particularly significant when compared with urban area.
* Also, number of total drivers is higher than total number of rides in urban cities area


![PyBer_fare_summary](https://github.com/Meghajain84/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

* Looking at multiple-line chart, as we move from rural to suburban, suburban to urban areas, total fare increases and the trend is same throughout the plotted months. The gap between total fares between urban and suburban, and suburban and rural city types seems comparable.


## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
(1) As pointed in results section, number of urban drivers is more than number of total rides in urban area. So, the recommendation is to move drivers from urban area to suburban or rural areas. To encourage that, company can probably give more incentives to suburban and rural drivers.

By doing this, average fare per driver in urban area can reduce as total number of urban rides will remain same despite lowering the number of drivers. Similarly, average fare per driver in rural and suburban areas will  increase as respective total drivers' counts will increase in rural and suburban areas. 

This will address the disparity of average fare per driver among city types

(2) Increase urban fare rate as we see average fare per ride is low in urban areas. By doing this, average fare per ride will increase in urban areas.This will address the disparity of average fare per ride.

(3) To promote increase in rides in rural and suburban areas, offer a free ride after certain number of rides only in suburban and rural areas. Thus, encouraging more rides in suburban and rural areas and bringing the average fare per ride down in these areas.


