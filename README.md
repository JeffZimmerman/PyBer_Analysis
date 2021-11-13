# PyBer_Analysis: /i/An Examination Ride-Sharing Data Across City Types/

## Overview
The purpose of this analysis was to resample data on ride-sharing services to better focus specifically on differences between types of cities, defined as Urban, Suburban, and Rural. New dataframes were created using Matplotlib functionality to merge csv files, reorganize, resort, and relabel the data into a more ideal form. The specific application was identified as creating effective visualization of the data for presentation to the CEO of a ride-sharing company, herself well-versed in data analytics and data visualization.

## Results
Based on the task of comparing data from different city types over time, a multiple-line chart was deemed the best method for communicating these differences. Daily data was aggregated into weekly intervals, and multiple cities consolidated based on their geographical type, which downplayed individual variations among a single type while highlighting the contrasts across these types. While ride-sharing services in all three city types showed variation in the fares collected based on date, each stayed within a distinct range throughout the year. 

![image](https://user-images.githubusercontent.com/91562577/141605686-5f80d907-7668-46e3-b2c3-cd6a66c0cd9b.png)

However, further examination of the original dataframe made from merging csv files offers some suggestive clues regarding the most salient information about the differences among city types ommitted from the line chart. The total amount of fares collected for each city type has an inverse relationship to the average fare collected per driver. The significant differences in total number of drivers for each city type offers some explanation for this, even while the average fare per ride is relatively close for each type.

![pyber_summary_df](https://user-images.githubusercontent.com/91562577/141605930-e918c6a6-dda8-40bb-bf27-2fb21276eed0.png)

## Summary

* Based on an initial view of the data based on the line chart, it is clear that urban areas generate significantly larger numbers in fares. Based on that information alone, it is clear that a ride-sharing company has a lot to gain from having a presence in large cities. The total number of rides is high, as are the number of drivers, so from volume alone a large amount of fares can be collected in total, even as the average fare per ride is lower than in other city types.

* Returning to the initial merged dataframe, there are factors worth considering besides total fares collected. Filtering by city type shows some possible opportunites besides the total fares collected, which obviously favors urban areas. Fares per ride are higher in rural areas, but not drastically so, while the lower number of total drivers in rural areas may have led to the much higher average fare collected per driver. Focusing a ride-sharing business on these areas suggests a strategy that benefits riders (by not having signficantly higher ride costs), while being a huge boon to drivers.

* In comparing city types there are some differences that are not particularly surprising, in that the line chart shows a higher number of total fares collected in urban cities compared with suburban and rural areas, which is so distinct that identifying population density alone might explain a lot. However, the logic behind these three designations is not fully clear from the dataset, so there may be more insights to be found by breaking the data into more types, or reworking the specific point at which a suburban area is deemed distinct from rural or urban, for example. The multiple-line chart mostly shows these three groups to have large differences in total fares collected. Focusing on four specific months doesn't seem to add anything, except to suggest that the specific conditions (weather, holidays, etc.) of each date did not affect each type uniformly. These three city types may each require their own business strategy, as the most salient consideration to emerge from the data is that each type is not like the others. 



