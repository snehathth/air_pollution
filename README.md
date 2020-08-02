# TIME SERIES ANALYSIS OF POLLUTANT LEVELS IN SAN DIEGO
Our focus on this project was on the 4 pollutants (Nitrogen Dioxide, Sulphur Dioxide, Carbon
Monoxide and Ozone)levels in San Diego. The US pollutants data was available on data.world.
We pre-processed the data to focus on one city, one pollutant (No2) for univariate Analysis
and the interaction of 4 pollutants with each other for multivariate analysis. The data was
stationary, and we found seasonality repeating every 12 months. No drastic changes or
outliers spotted in the data.

For univariate analysis, we came up with 10 different models, tested the efficiency in
prediction through aic and rolling forecasting. After choosing the final model, we predicted
the level of pollutants for the next 12 months and compared it to the test data. The actuals
were well within the 95% confidence interval. This can be owed to a consistent pattern and
seasonality in the data.

For multivariate analysis, we investigated the scatter plot to understand the correlation
between the pollutants. There was a significant relationship found between No2 and the
other pollutants. S02 remained uncorrelated. We decided to make a linear regression model
and build analysis on that. The resulted prediction was well within the range, but time series
prediction gave better results. We ventured further into the VAR model. Since the lag was at
4, the model was bigger than anticipated. We decided to finalize the linear regression model
for the multivariate analysis. 
