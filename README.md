# House_Price_Prediction
A machine learning project to predict housing prices using linear regression and feature engineering on the California Housing Dataset 

HOUSE PRICE PREDICTION
A comprehensive machine learning project in Python to predict housing prices in California, following the complete data science workflow—from data exploration and preprocessing to advanced feature engineering and model building.

OVERVIEW
This project uses the California Housing Prices dataset and demonstrates:
Data exploration and visualization to understand correlations and distributions.
Data cleaning (handling missing values).
Advanced feature engineering, such as log transformations and ratio features.
Conversion of categorical features to numeric format using one-hot encoding.
Building and evaluating predictive models:
    Linear Regression
    Random Forest Regressor
Model improvement with scaling and hyperparameter tuning.

FEATURES
Data loading and exploratory analysis (Jupyter notebook setup).
Handling missing data and skewed features.
Visualization using Seaborn and Matplotlib (histograms, correlation heatmaps, geospatial plots).
Feature engineering: creation of new ratio-based columns and log-transformed features.
Conversion of 'ocean_proximity' categorical variable into dummy variables for modeling.
Regression modeling with scikit-learn pipelines.

USAGE
Clone the repository and download the California Housing Prices dataset.
Install required libraries:
   bash
   pip install numpy pandas scikit-learn matplotlib seaborn
Open the Jupyter notebook (.ipynb file) or Python scripts and run step-by-step.

PROJECT STRUCTURE
data/ – Contains the housing CSV dataset.
house_price_prediction.ipynb – Main notebook with all data analysis and modeling steps.
figures/ – Generated plots and visualizations (optional).
requirements.txt – Required Python package list.

KEY RESULTS
Identified strong predictors, such as "median_income" and proximity to the ocean.
Linear Regression achieved baseline performance.
Random Forest Regressor improved prediction accuracy after hyperparameter tuning.

REFERENCES
California Housing Prices dataset (Kaggle)
Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn official documentation

LICENSE
This project is for educational purposes. Please cite appropriately if sharing or adapting the code.
