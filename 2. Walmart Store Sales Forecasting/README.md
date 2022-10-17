# Business Problem
We are provided with historical sales data for 45 Walmart stores located in different
regions. Each store contains a number of departments, and we are *tasked with predicting
the department-wide sales for each store*.<br><br>
In addition to this, Walmart runs several promotional markdown events throughout the year.
These markdowns precede prominent holidays, the four largest of which are the Super
Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are
weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge
presented by this dataset is modelling the effects of markdowns on these holiday
weeks in the absence of complete/ideal historical data

## Approach
Even though this looks like a forecasting problem, the dataset provided does not have the proper timeseries data to do a simple Forecast model.<br>
Also there are other features to be considered like holiday sales,size of the store etc to be able to do a comprehensive analysis of the dataset.<br>
<br>
After initial EDA, Regression was the decided model and thus **Random Forest Regressor** was chosen, as we are dealing a number of different stores,
and incorporating the average data from each of them would bring some valuable insight in the prediction.

