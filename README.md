# Surf's Up:  Analyzing Weather Observations
## Overview
In order to find the optimal locaiton for a new surfboard/ice cream shop, a thorough analysis of weather patterns was conducted using sqlalchemy and Flask.  In particular, the monhts of June and December were analyzed to find the key differences between those periods.
## Results
In comparing the key metrics across those two periods, here were the largest differences identified:
* Minimum temperatures showed the largest gap between the two sets of summary statistics, with December showing a minimum temperature of 56, while June's lowest temp was 64.  
* The median temperatures showed slight differences, with December (71) below June (75).
* The max temperatures were very similar across those two months, with June at 85 while December was at 83.
# Summary
There were a sizable amount of data points across both months (over 1,500 observations each), which suggests that the sample size is large enough to trust these results.  However, further analysis could be done to compare the observations occurring by location, and ensure there is a balance of weather station coverage across both periods.  Additionally, since the precipitation amounts were excluded from this analysis, it would be good to incorporate the monthly summary statistics for precipitation as well.  Overall, there doesn't seem to be a bad month in Hawaii to open an ice cream/surfboard shop.  