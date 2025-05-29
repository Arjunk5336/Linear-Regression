# Housing Price Prediction using Linear Regression

This project demonstrates a basic implementation of Simple Linear Regression using Python to predict housing prices based on the area of the property. It utilizes data preprocessing techniques, model training, evaluation, and visualization to provide insights into housing price trends.

Tools and Libraries Used:

Python

Pandas – Data manipulation

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning model and evaluation


Dataset:

The dataset used is a CSV file containing housing data, including:

area (numeric)

price (target variable)

Other categorical variables (which are one-hot encoded)


Project Workflow:

1. Data Loading: Reads the housing data from a CSV file.


2. Data Preprocessing: Applies one-hot encoding to handle categorical variables.


3. Simple Linear Regression:

Uses only the area feature to predict the price.

Splits the dataset into training and testing sets.

Trains a linear regression model using scikit-learn.



4. Model Evaluation:

Computes Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

Outputs model coefficients (slope and intercept).



5. Visualization:

Plots a scatter plot of actual vs predicted prices with the regression line.
