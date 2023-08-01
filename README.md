# Code Description
The Python script uses the scikit-learn library to perform Linear Regression and Lasso Regression on the car data to predict the selling prices of the cars.

# Data Preprocessing:

The dataset is read from the CSV file using Pandas.
Categorical variables ('Fuel_Type', 'Seller_Type', 'Transmission') are encoded into numerical values.
The 'Car_Name' and 'Selling_Price' columns are dropped from the feature matrix 'X' and stored in the target variable 'Y'.
Linear Regression:

The data is split into training and testing sets using the train_test_split function.
The Linear Regression model is trained using the training data.
Predictions are made on the training data to evaluate the model's performance using R-squared error.
Actual prices vs. predicted prices are visualized for the training data.
Testing Linear Regression:

The model is evaluated on the test data using R-squared error.
Actual prices vs. predicted prices are visualized for the test data.
Lasso Regression:

Lasso Regression model is trained using the training data.
Predictions are made on the training data.
Actual prices vs. predicted prices are visualized for the training data.
Error Calculation for Lasso:

R-squared error is calculated for the Lasso Regression model using the training data.
# Results
The script will display the R-squared error for both Linear Regression and Lasso Regression on the training data. Additionally, it will visualize the actual prices vs. predicted prices for both training and test data.
