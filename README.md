# surfs_up

## Overview

The purpose of this analysis was to quantify weather data for a fictional business venture on Oahu, Hawaii. The venture relates to tourism and surfing, and the success of the venture is dependent on the weather of the business location. A dataset was provided that offers weather information including temperatures and precipitation from different weather stations over a multi-year period. The information was extracted and summarized using Jupyter Notebooks, the Pandas library, and SQLAlchemy/SQLite.

The two deliverables were summary temperature statistics from the months of June and December, respectively, over the multi-year period captured by the data.

Summary statistics for June:
 

![June temps PNG](https://user-images.githubusercontent.com/100863488/165541199-2cee3fe7-4755-4eab-8ab3-6eda912cb7f9.png)


Summary statistics for December:
 

![Dec temps PNG](https://user-images.githubusercontent.com/100863488/165541295-11bf6482-52a2-40ed-a60b-d31e519163a5.png)



## Results

The major takeaways from the two deliverables included:

- The temperatures appear relatively constant year-round. The mean temperature recorded in June was 74.94 degrees F, and the mean temperature recorded in December was 71.04 degrees F. 
- The temperatures may to be warm enough to support surfing year-round. The minimum temperature recorded in June was 64 degrees F, and the minimum temperature recorded in December was 56 degrees F. 
- The temperatures do not vary much in a given month. For June, the interquartile range is 73-77 degrees F, and for December, the interquartile range is 69-74 degrees F. The standard deviation for June is 3.26, and the standard deviation for December is 3.75.



## Summary

In conclusion, the temperatures appear to be agreeable and stable enough to support a business dependent on good weather for success. 

However, additional data would be welcome for supporting these conclusions. The queries above investigated **temperature** of all locations but not other variables. Additional queries we could perform on this dataset for helpful information would be:

- Creating similar dataframes and summary statistics regarding **precipitation** amounts for June and December. 
- In addition, since the business will have a brick-and-mortar store, the business's specific location on the island will influence its success. Since this dataset includes information from weather stations in different physical locations, we could write queries to determine which station recorded the highest average temperature, or the lowest average precipitation, etc., in order to identify which weather station location offers the best weather for surfing. 
 

