## Prediction for bike sharing daily dataset

**Problem statement** : Predication of bike rental count hourly or daily based on the environmental and seasonal settings.

#### Steps Followed:
* Loading Data
* Data Analysis
* Data Visualization (line charts are useful for Time Series)
* Model Building
* Prediction: with Holidays
* Model Evaluation

**Time Series Forecasting with Facebook Prophet:**

Facebook developed an open sourcing Prophet, a forecasting tool available in both Python and R. It provides intuitive parameters which are easy to tune. It helps to generate meaningful predictions for a variety of problems in business scenarios.

The Prophet uses a decomposable time series model with three main model components: trend, seasonality, and holidays.
They are combined in the following equation:

y(t)= g(t) + s(t) + h(t) + εt

g(t): piecewise linear or logistic growth curve for modeling non
periodic changes in time series

s(t): periodic changes (e.g. weekly/yearly seasonality)

h(t): effects of holidays (user provided) with irregular schedules

εt : error term accounts for any unusual changes not accommodated by the model
