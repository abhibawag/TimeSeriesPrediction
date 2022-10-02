# TimeSeriesPrediction
Made by - Abhishek Bawa

## Task
Need to predict the parameters Para-9, Para-10, Para-11, Para-12, and Para-13 for year 10 from a 10-year timeseries dataset.

## Model Used
I have used Light Gradient Boosting Machine for solving this problem.

## What I did?
I have loaded all the required libraries and the dataset provided. Anomalies are removed and NA are replaced with zeroes to ensure correct naming of subsections. Test dataset is extracted which have year == 10. LGBM Regressor is used for training and testing purposes. Time Series is given to regressor section wise and year 10's Parameters Para-9, Para-10, Para-11, Para-12 and Para-13 are predicted. Plots for original and predicted values of these params are also shown.

## Results
The RMSE value of the model is 68.76
