# Surfs Up
a weather analysis of a prospective location for a surf shop/ice cream parlor

## Overview
I am an entrepreneur looking to open a surf shop/ice cream parlor. However, in order to be profitable, I would need to do good business year-round. Few places in the USA would permit such a place to remain open all year, but our prospective location in Oahu is one of them. Even so, out of abundance of caution, my financial backer has asked me to use my data analysis tools including sqlalchemy to analyze temperature data for June and December to make sure we can stay open during those months.

Overview of the analysis: Explain the purpose of this analysis.

## Results

Here are the summary statistics for the June temperatures.

![june](https://github.com/LiShanDa2021/surfs_up/blob/main/june_temps.png?raw=true)

And here are the summary statistics for the December temperatures.

![dec](https://github.com/LiShanDa2021/surfs_up/blob/main/dec_temps.png?raw=true)

* As you can see, the temperature profiles for June and December are fairly similar.
  + The mean temperatures are within a few degrees
  + The maximum temperatures are similar -- within 2 degrees.
  + The standard deviations are similar -- and small at 3-4 degrees.

* The weather is pleasant overall (to a Minnesotan at least) in both months.
  + The mean temperatures are both above 70.
  + The lowest temperature in December is 56.
  + The temperature never reaches 90 degrees.

## Summary

The results show that -- as far as temperature is concerned -- that a year-round business model is sustainable. First of all, we can safely say it never gets too hot. The maximum temperatures for both months are in the 80s -- perfect beach weather. We won't need to worry about our ice cream melting too fast. Secondly, it is unlikely to get too cool during business hours. The minimum December temperature of 56 degrees is conducive neither to surfing nor ice-cream eating. However, the mean temperature in December was 71 degrees with a standard deviation of 4 degrees meaning most days would fall between 67 and 75 degrees. It might be cool for those living in Hawaii but ideal for tourists from the cold mainland.

While we have good data, we must continue to conduct further analyses. We should also look at precipitation data from the two months. It may be warm, but no one wants to surf and eat ice cream in the rain. We should also look at cloud data; a 70 degree day might be a fine day for surfing and ice cream if it is sunny but unpleasant if it is cloudy. We can tentatively say the outlook is good but, before we move forward, we should query the database for cloud and rain data.

