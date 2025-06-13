Title:
**Forecasting Seasonal Trends for Dairy Queen Using Google Trends Data**

Author:
Kenji Wagner

Dataset Name:
Dairy Queen Google Trends Time Series (Monthly Data, 2009–2019)

Data Source:
Google Trends – Downloaded from Google Trends and augmented in R

Objective:
To analyze and forecast seasonal search interest in Dairy Queen using time series modeling. The goal is to understand how consumer search interest fluctuates throughout the year and assess the effectiveness of different forecasting models for seasonal business analysis.

Final Models Used:

Manual SARIMA: (1,1,1)(0,1,1)[12]
RMSE: 8.19 | MAPE: 11.65%
Auto ARIMA: (2,0,0)(0,1,1)[12]
RMSE: 5.80 | MAPE: 6.99%
Holt-Winters Additive:
RMSE: 11.95 | MAPE: 15.28%

Conclusions:
The data exhibited strong seasonality and an increasing trend, typical of a business like Dairy Queen that peaks in popularity during the warmer months.
The SARIMA models outperformed the Holt-Winters model, which struggled with capturing more nuanced time dependencies, using AICc, exhibiting the strength of the metric.
The auto.arima-selected SARIMA model was the most accurate, outperforming the manually tuned SARIMA model.
The final model provided a reliable forecasting tool that businesses like Dairy Queen can use to anticipate customer interest and adjust operations accordingly (e.g., marketing, staffing, and inventory decisions).
This project illustrates the value of Google Trends as a data source for analyzing consumer behavior, particularly for seasonal businesses.
