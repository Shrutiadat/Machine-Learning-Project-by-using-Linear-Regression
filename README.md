1. Data Loading and Exploration:
- The project starts by importing necessary libraries, including Pandas and NumPy.
- The lung capacity data ('LungCapData.csv') is loaded using Pandas, and its shape and missing values are examined.
- The data types of columns and unique values in the 'Smoke' column are explored.

2. Data Preprocessing:
- The 'Smoke', 'Gender', and 'Caesarean' columns are converted from object types to numeric types using the replace method.
- The dataset information is displayed again to confirm the changes.
  
3. Sampling:
- The project uses scikit-learn's train_test_split function to split the dataset into training and testing sets.
  
4. Model Building:
- A linear regression model is chosen, and the necessary functions from scikit-learn are imported.
- An instance of the linear regression model is created (LinearRegression()), and it is trained using the fit function on the training data.
- The R-square and adjusted R-square values are calculated to evaluate the goodness of fit.
  
5. Model Evaluation:
- The coefficients (beta values) and the intercept (beta not value) of the linear regression model are obtained.
- Predictions are made on both the training and testing sets.
- The model's performance is evaluated using various metrics:
  
    -Error is calculated as the difference between actual and predicted values.
    -Mean Square Error (MSE) is computed.
    -Root Mean Square Error (RMSE) is calculated.
    -Mean Absolute Percentage Error (MAPE) is calculated.
  
6. Results and Conclusion:
- The project concludes by providing insights into the model's performance through metrics like R-square, adjusted R-square, and error metrics (MSE, RMSE, MAPE).
- These metrics give an indication of how well the linear regression model fits the lung capacity data and how accurate its predictions are
