# Forecast-Risk_Project
## Oil prices analysis

### Introduction
#### This dataset contains the daily price of oil from 1987 till 2021 and was found on Kaggle provided by Frank Wu. The index is the daily date variable and the forecasted variable is price. Forecasting the price of oil can allow for us to better understand why the price of gas is increasing/decreasing and make better decisions on when to invest.

### Exploratory Analysis and Visualization
#### In terms of price, starting at the beginning all the way up til 2007-2008 there is upward trend. Following that there is a huge drop off (or decrease) that is followed by another upward trend that is then followed by another drop off. Also, the cycle seems to be unseasonal or unpredictable. There was a high pulse in 2008 which can be explained by an energy crisis. There was a huge demand for oil from developing economies and tension from the Middle East that is most likely responsible for the high oil prices.
#### By classifying per year, you can see that in the 1900s oil prices were at its lowest. The closer you get to the 2000s and on you can see that oil prices were gradually increasing until its peak in 2008. Around 2014, you can assume that there was an event that caused oil prices to skyrocket again. Research tells us that oil production was disrupted in the Middle East and parts of Africa which halted 1 million barrels of petroleium a day. This is a clear indicator as to why oil prices would be so much higher than average.
#### In regards to Month and weekday, the subseries for each month/weekday look very similar telling us that there isn't a huge seasonal difference between the varying months/weekdays. Also, after comparing the lags of itself to eachother you can see that each lag seems to be going in the same direction meaning that there is a pattern and suggests that the data is not random.
#### When using a geombar to compare price to Month and Weekdays, it suggests that on average that earlier in the week and earlier in the year, oil prices are at its lowest. However, when looking at the data as a whole, there doesn't seem to be a clear pattern that suggests that this is entirely true. When just comparing Month and Quarter, the oil prices on average are relatively the same. In regards to comparing the Year to Weekdays, oil prices seem to rise over the years but there is no clear correlation that the day of the week has any affect.
#### Q3 so (months 6-9) have the highest price for oil, Q1 (months 1-3) have the lowest price for oil

### Model Fitting
#### The mean of the residuals are not close to zero. There does not seem to be a clear pattern (unpredictable) but the residuals are not randomly dispersed meaning a non linear model would probably fit best. For ACF, there does not seem to be any seasonality since all lags have a high positive correlation. However there is a slow decrease in ACF as you get closer to a higher lag. The histogram is mulitmodal meaning that there are three or more peaks in the distribution. This tell us that the data is not normally distributed and that the data has several different patterns.


