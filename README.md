Car Price Prediction with Machine Learning

Overview
This project builds a machine learning regression model to predict the selling price of used cars based on various features such as manufacturing year, present price, kilometers driven, fuel type, transmission type, and ownership history.

The objective is to demonstrate end-to-end implementation of a regression problem including data preprocessing, feature engineering, model training, evaluation, and visualization.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Workflow
Data Cleaning & Preprocessing
Encoding Categorical Variables
Feature Selection
Train-Test Split
Linear Regression Model Training
Model Evaluation using MAE, MSE, and R² Score
Visualization of Predictions

Model Performance

R² Score ≈ 0.84
MAE ≈ 1.22
MSE ≈ 3.53
The model explains approximately 84% of the variance in car prices, indicating strong predictive performance for a linear regression approach.

Key Insights
Present price has the strongest positive influence on selling price.
Newer vehicles retain higher resale value.
Increased kilometers driven negatively impacts resale price.
Ownership history slightly reduces market value.

Conclusion
This project demonstrates how regression models can be applied in real-world price estimation systems such as used car marketplaces. The workflow reflects industry-standard data science practices from preprocessing to evaluation.
