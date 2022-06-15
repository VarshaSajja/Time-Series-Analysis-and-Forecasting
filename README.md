# Flight Delay Predictions with weather
**Introduction**

In this project, the best way to predict how long a flight would be delayed if the weather was bad has been discovered. The analysis consisted of 2 years of data from two different sources. For the flight data, dataset from the Bureau of Transportation Statistics Carrier On-Time Performance data is used, and filtered it to Chicago O’Hare Airport. For the precipitation data, the U.S. Local Climatological Data from the National Oceanic and Atmospheric Administration is used, and filtered that data to the O’Hare zip code.

**Summary**

The weather data was at the hourly level, and the flight data was by individual flight, so the data has been aggregated to daily and weekly levels. For the daily level, summation of the precipitation on a daily level and average of the flight delays for the day has been done. 
For the weekly data, I have summed both the precipitation and the total flight delay times for the week. The data sets were joined on the date column specifically.

**Conclusion**

Variety of models were tried to determine what's the best way to model our forecast would be. Through this analysis we determined the best way would be to use an x-reg ARIMA model as that produced the best type of model to use and it gave us something to model, and we got pretty good fits for our models. 
When looking at the results to determine what model, the daily or weekly, gave us the best predictions when we used the mean absolute percentage error and tried to minimize that as much as possible. The daily model had a MAPE of 54% while the weekly model had a MAPE of 37%. 
The results were that the weekly model performed better than the daily model.
The results showed us the confidence to forecast of our small data set and just looking at one airport and one type of delay, but we only scratched the surface of the types of analysis that could be done to forecast flight delays. More illustration has be done if there were more factors that influence the flight delays apart from weather. 
