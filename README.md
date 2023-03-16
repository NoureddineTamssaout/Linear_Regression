# Linear_Regression
Linear regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. The goal of linear regression is to find a line (or hyperplane) that best fits the data by minimizing the sum of the squared distances between the predicted values and the actual values.

In a simple linear regression, there is only one independent variable, and the line of best fit is a straight line.

So, in this program, we first import the necessary libraries. We then define the input data (X) and output data (y). Next, we split the data into training and testing sets using the train_test_split function. We then create a LinearRegression object, fit it to the training data using the fit method, and use it to make predictions on the testing data using the predict method.

We also calculate the mean squared error of the predictions using the mean_squared_error function. Finally, we print the slope and intercept of the line of best fit using the coef_ and intercept_ attributes of the LinearRegression object, and print the mean squared error.
