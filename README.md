# Linear Regression with Gradient Descent
This notebook demonstrates a simple implementation of linear regression using gradient descent.

Data
The notebook uses data from txt1.txt, which contains two columns: 'Population' and 'Profit'. The goal is to predict 'Profit' based on 'Population'.

Steps
Import Libraries: Import necessary libraries (numpy, pandas, matplotlib, seaborn).
Load Data: Load the data from txt1.txt into a pandas DataFrame.
Data Exploration: Display the head and descriptive statistics of the data, and visualize the data using a scatter plot.
Prepare Data for Gradient Descent:
Add a column of ones to the input features (X) for the intercept term.
Separate the features (X) and the target variable (y).
Convert pandas DataFrames to numpy matrices.
Initialize the parameters (theta) to zeros.
Cost Function: Define the cost function (mean squared error).
Gradient Descent: Implement the gradient descent algorithm to minimize the cost function and find the optimal parameters (theta).
Visualize Results:
Plot the best-fit line obtained from the gradient descent on the scatter plot of the data.
Plot the cost history over iterations to show the convergence of the gradient descent algorithm.
