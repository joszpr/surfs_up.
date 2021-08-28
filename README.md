# Surf_Up_Analysis

## **Overview** ##

Weather analysis performed as part of the business plan for Surf N Shake shop intended for development at Oahu island, Hawaii. The shop concept is to provide a location that can sell products and services related to surfing along with selling ice cream as comfort in sunny days. The results of the analysis will be presented to the board of investors alongside primary investor, W. Avy. The goal was to find any useful insights regarding the amount of rain that is to be expected during a year and temperature fluctuations in the island that may impact the success and profitability of the surf shop. 

## **Methodology** ##

The analysis utilized a weather dataset that recorded different environmental metrics at Oahu during the years 2010 until the last months of 2017. The data contained daily metrics from 9 different weather stations around the island. Every station measured temperatures and precipitation amount daily. The data was processed using Python via Jupyter Notebook with the inclusion of SQLAlchemy and SQLite. 

## **Results** ##

**1.	Temperature statistics for the months of June and December between 2010 and 2017.**

![Temperature Summary Distribution](https://user-images.githubusercontent.com/85839235/131205606-854b2006-7597-4091-acc3-a451d29e3277.jpg)


-    The average temperature for June was 74.9 °F and for December was 71 °F. 
-    The maximum temperature for June was 85 °F and for December was 83 °F. 
-    The minimum temperature for June was 64 °F and for December was 56 °F. 

**2.	Precipitation statistics for the months of June and December between 2010 and 2017.**

![Precipitation Summary Distribution](https://user-images.githubusercontent.com/85839235/131205615-d97fb9bb-bf9e-4fb9-b3f3-72d7b2f890de.jpg)


-	The average precipitation for June was 0.14 mm and for December was 0.22 mm. 
-	The maximum precipitation for June was 4.43 mm and for December was 6.42 mm. 
-	The minimum precipitation for was 0 for the days when no rain was recorded. 

**3.	Comprehensive Temperature Analysis**

###### Frequency distribution of temperature fluctuations using all the yearly data. ######
![Temperature Distribution](https://user-images.githubusercontent.com/85839235/131043842-6b950937-5b46-422c-a872-9627a80863f2.png)

###### Average temperature fluctuations by month using all the yearly data. ######

![Monthly Average Temperature](https://user-images.githubusercontent.com/85839235/131043865-65100c0f-fda1-4dcc-a2e8-861db8456de2.png)

**4.	Comprehensive Precipitation Analysis**

-	Frequency distribution of precipitation fluctuations using all the yearly data.
    
![Precipitation Distribution](https://user-images.githubusercontent.com/85839235/131043892-fac9cccb-216b-41ed-9e60-6a43ec318c71.png)

-	Average temperature fluctuations by month using all the yearly data.
![Monthly Average Precipitation](https://user-images.githubusercontent.com/85839235/131043910-f84cd204-d23f-4d37-8976-25251b8e08a4.png)


## **Summary** ##
1.	The original focus of the analysis was regarding the temperature data for the months of June and December. The temperature summary statistics shows a slight difference in the average temperature between the two months, 74.9 °F for June and 71 °F for December. The Maximum temperature followed a similar pattern, 85 °F for June and 83 °F for December. Where the two months differed the most was in the minimum temperatures, 64 °F and 56 °F respectively. There seems to be little fluctuations in temperatures between the two months and provide good conditions for surfing which would attract tourists and locals. 

2.	Additional analysis was performed with focus on the months of June and December regarding the precipitation amount the island received. With the insights provided in the Precipitation Summary Statistics, the data shows that June received less days of rain compared to December. The pattern remains the same on for the heaviest rainfalls. Another noteworthy trend is that the data is heavily skewed between the Average values and the Minimum Value of 0, for both months. This shows that most days there wasn’t any recorded precipitation and the Maximum values recorded seem to be outlier values and those heavier rainfall seem to be infrequent. 

3.	The analysis was extended in order to look at the Temperature and Precipitation fluctuations distribution in order to corroborate the insights obtained from the summary statistics using all the data. The Temperature Histogram indicates the temperature mostly fluctuates between the 70 °F and 78 °F. The Precipitation Histogram illustrates little to no rain recorded throughout the island. 

4. 	The data was parsed in order to compare the Temperature and Precipitation variables my month in order to inquire about any possible patterns. The Monthly Average Temperature chart shows the warmer months to be in the summertime, which is expected due to the location of the island in comparison to the equator. The Monthly Average Precipitation chart demonstrates which months tend to be the ones with more frequency and amount of rain within the years of data. The highest precipitation seems to be during December with November leading up to it. The second month with highest precipitation is March. 

## **Conclusions** ##

1. 	Oahu seems to have steady yearly temperature fluctuations which would be prime for local surfers to frequent the beach and tourist to travel and increase foot traffic for a surfing and ice cream store. 

2.	Precipitation amounts seem to be acceptable for an island close to the equator and doesn’t seem to pose a problem for surfing year-round. 

3.	Rainfall patterns observed for the months of March, November and December, as well as the lower temperatures between December and March, provide an opportunity to adjust the food offerings. Further analysis in sales data may be needed in order to identify if it may be profitable to serve warm drinks or comfort sweets associated with rainy days or cold days.
