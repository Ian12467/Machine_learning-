# Linear regression

### Mnemonics

* MAE - The Mean Absolute Error
* RMSE - Root Mean Squared Error
* MSE - Mean Squared Error

## Steps

* Import training models from sklearn and math module.
* Load the data.
* Split data for training and testing sets.
* Fit the linear regression model on the training data.
* predict charges on test data.
* Evaluate the model using MAE, RMSE, and MSE.

### Insights from the analysis

* The model's predictions on the target variable (charges) have an average error of 4367.523606000216 in either direction.
* The Mean Squared Error (MSE) of 38191757.68319815 indicates the average squared difference between the actual and predicted values.
* The Root Mean Squared Error (RMSE) of 6179.948032402712 is the square root of the MSE and represents the standard deviation of the errors.

### Conclusion

* The RMSE value seems high, indicating that the model may not be fitting the data well. Further analysis may be needed to improve the model's performance or trying different algorithms.
