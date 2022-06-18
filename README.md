# bulldozer-bills
## This is the implementation of random forest regressor on a time series data of bulldozer prices.<br>
The code includes:<br>
1. Feature engineering : This was done in order to add some more columns of time , for eg. date, month etc. in the dataframe.<br>
2. Data preprocessing : This step was done to change the data into a form that can be inferrred by the model, like changing string data to categorical and replacing null values with median.<br>
3. Fitting the model : Random Forest regressor is used to fit the train data into, and sales price column is dropped from train_x and named as train_y. Loss function is chosen as RMSLE.<br>
4. Hyperparameter tuning : In the penultimate step, randomizedsearchCV and gridsearchCV was used to find the best hyperparameters for the model, like max_depth, max_features etc.<br>
5. testing the accuracy : This final step involved preprocessing the test data and fitting it into the model to find the accuracy and other metrics of the model.
