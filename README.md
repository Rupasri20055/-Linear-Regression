# -Linear-Regression
Task 3: Linear Regression

About this Task:
Hey! This task was about understanding how Linear Regression works using the Ames Housing dataset. I built a simple linear regression model to predict house sale prices based on the house's above-ground living area.

What I did in this task:

1️ Imported the Ames Housing dataset using Pandas.

2️ Checked basic info like shape, data types, and missing values.

3 Handled missing values — removed rows where important columns like SalePrice or Gr Liv Area were missing.

4️ Selected Gr Liv Area as the feature (independent variable) and SalePrice as the target (dependent variable).

5️ Split the data into training and testing sets (80% for training, 20% for testing).

6️ Fitted a Linear Regression model using sklearn.linear_model.

7️ Made predictions on the test set.

8️ Evaluated the model’s performance using MAE, MSE, RMSE, and R² score.

9️ Plotted a scatter plot with the actual vs predicted values and drew the regression line.

10 Finally, printed the intercept and coefficient (slope) to understand the relationship between Gr Liv Area and SalePrice.
