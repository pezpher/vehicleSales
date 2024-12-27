# vehicleSales
Analyzes automotive sales data using statistical methods. It first imports necessary libraries and then loads data from two local CSV files, merging them into a single DataFrame. After cleaning and preparing the data, it performs an Ordinary Least Squares (OLS) regression analysis to model the relationship between automotive sales and independent variables such as 'FEDFUNDS', 'UNRATE', and 'INFLATION'. The model's performance is evaluated using the R-squared value, and the Variance Inflation Factor (VIF) is calculated to assess multicollinearity among the variables.

The code then visualizes the relationship between actual and predicted sales using a scatter plot, and plots residuals against predicted values to assess the model's assumptions. It also applies an ARIMA model (Autoregressive Integrated Moving Average) to analyze the time series component of the automotive sales data, further evaluating its performance using R-squared and Mean Squared Error (MSE).

Finally, the code explores the impact of a log transformation on the data and repeats the OLS regression and ARIMA analysis, comparing the results and model performance with the original, untransformed data.
