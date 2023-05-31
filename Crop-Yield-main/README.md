# Crop Yield prediction

This is my first attempt at using data. I needed it for college.

I started by loading the necessary libraries, including pandas, numpy, matplotlib, seaborn, scikit-learn, and scipy. Then, I read in a dataset of housing prices using the pandas library, and I explored the dataset by looking at the head, info, and summary statistics.

After that, I split the data into training and testing sets using the train_test_split() function from the scikit-learn library. Then, I created a baseline model using the mean housing price and calculated its mean squared error and R-squared values.

Next, I performed linear regression on the training data using the LinearRegression() function from the scikit-learn library, made predictions on the testing data, and calculated its mean squared error and R-squared values.

I tried different types of normalization techniques such as MinMaxScaler, StandardScaler before performing the regression analysis.

Furthermore, I performed Ridge regression, Lasso regression, and ElasticNet regression on the training data, made predictions on the testing data, and calculated their mean squared error and R-squared values. I also performed Support Vector Regression, Random Forest Regression, and Gradient Boosting Regression on the training data, made predictions on the testing data, and calculated their mean squared error and R-squared values.

Finally, I compared the performance of all the models by looking at their mean squared error and R-squared values, and concluded that Gradient Boosting Regression performed the best among all the models.
