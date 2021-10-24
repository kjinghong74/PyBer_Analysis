# PyBer-_Analysis
## Overview of the analysis:
  In this project, Python and Pandas skills were used to analyze the ride-sharing data by city type (Urban, Suburban adn Rural). First, the ride-sharing data were groupby() city type to get the total number of the rides, total number of the drivers, and the total ride fares for each city type, then the average fare per ride and average fare per driver for each city type were caclulated. A DataFrame is established to show these data. In the second part, new DataFrame was created using pivot() function, and the resample() function was used to show the sum of the fares for each week between the date range of 2019-01-01 through 2019-04-29. Finally, a multiple-line graph was generated to show the total weekly fares for each city type 

## Results:
  From the table below, we can see that:
  - In Rural cities, the total rides, total drivers and total fares are only 125, 78 and $4,327.93, respectively, which is significantly less than other two city types (Suburban and Urban). Suburban cities have 625 total rides, 490 total drivers, $19,356.33 total fares, about 5 times more than Rural cities. Urban cities have the most total rides number(1625), total driver number(2405) and total Fares($39,854.38). Taking the average calculations, the average fare per ride and average fare per driver is most expensive in Rural cities, less expensive in suburban cities, and the lest expensive in Urban cities 



![dataframe_citytype](https://user-images.githubusercontent.com/90361056/138576490-28ffb491-08ae-4901-904d-5ce128bd5837.PNG)
