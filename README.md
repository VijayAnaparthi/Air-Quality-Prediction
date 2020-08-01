# Air-Quality-Prediction
Predicting Air quality by using Machine learning supervised alogorithms.
## About Data set(AirPi Data - AirPi.csv file)

1. Data set contains 9 features and 1 target variable i.e air_quality.

2. It contains 14572 data points and i didvide data into 70%(train) and 30%(test).
3. Basically i am not did any exploratory data analysis on this dataset. If you are intrested you can contribute to that.
## Trained models
It is a regreesion problem so i trained 3 models i.e

1. Linear regression
2. Random forest regressor 
3. XGboost regressor

In this process i also did hyper parameter tuning by using Randomsearchcv then trained the model again.
## Performance metrices

1. Mean squared error(MSE)
2. Mean absolute percentage error(MAPE)
3. R2 score
## Conclusion

1. I found out XGboost regressor is less overfitting compare to remaning two models. But Random forest regressor giving the best results in terms of error.

2. So in above Airpi_output.csv file i added 3 more columns and appended predicted values of every model for each datapoint.
