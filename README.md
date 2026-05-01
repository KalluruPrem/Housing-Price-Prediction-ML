# Housing-Price-Prediction-ML
Machine learning project predicting housing prices using regression models, with feature transformation, model comparison, and evaluation metrics.

## What is this project?

This project predicts housing prices using machine learning.

It uses different features like crime rate, number of rooms, age of the house, and location-related factors to estimate the price of a house.

## Dataset

The dataset contains multiple features such as:

* Crime rate
* Residential land zoning
* Number of rooms
* Age of property
* Distance to employment centers
* Tax rate
* Socio-economic factors

Target variable:

* **Median house value**

## What was done in this project?

Step-by-step:

1. Loaded and explored the dataset
2. Performed univariate analysis (distribution plots)
3. Applied log transformation to handle skewed target variable
4. Performed correlation analysis using heatmaps
5. Visualized relationships between important features
6. Built regression models to predict housing prices
7. Compared model performance using evaluation metrics


## Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

## How models were evaluated

The models were evaluated using:

* **MAE (Mean Absolute Error)** → average error
* **RMSE (Root Mean Squared Error)** → penalizes large errors
* **R² Score** → how well the model explains the data

Higher R² indicates better performance

## Visualizations

This project includes:

* Feature distribution plots
* Correlation heatmap
* Scatter plots between variables
* Model comparison chart
* Residual plot

These visualizations help understand both the dataset and model performance.

## Cross Validation

Cross-validation was used to ensure that the model performs consistently across different subsets of the data.

## Result

The best model is selected based on the highest R² score and lowest error values.

## Author
Kalluru Prem
