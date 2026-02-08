

#  CodeAlpha – Car Price Prediction with Machine Learning

##  Project Objective

The objective of this project is to build a machine learning regression model to predict the selling price of used cars based on various vehicle attributes such as manufacturing year, present price, fuel type, transmission type, kilometers driven, and ownership history.

This project demonstrates an end-to-end machine learning workflow including data preprocessing, feature engineering, model training, evaluation, and visualization.


##  Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn


## Dataset Description

The dataset includes the following features:

* **Car_Name** – Name of the car
* **Year** – Manufacturing year
* **Present_Price** – Current ex-showroom price
* **Driven_kms** – Total kilometers driven
* **Fuel_Type** – Type of fuel used (Petrol/Diesel/CNG)
* **Selling_type** – Dealer or Individual
* **Transmission** – Manual or Automatic
* **Owner** – Number of previous owners
* **Selling_Price** – Target variable (resale price)


## Project Workflow

✔ Data Cleaning

✔ Handling Missing Values

✔ Encoding Categorical Variables

✔ Feature Selection

✔ Train-Test Split

✔ Linear Regression Model Training

✔ Model Evaluation (MAE, MSE, R² Score)

✔ Visualization of Actual vs Predicted Prices


## Model Performance

* **MAE:** ~1.22
* **MSE:** ~3.53
* **R² Score:** ~0.84

The model explains approximately **84% of the variance** in car selling prices, indicating strong predictive performance for a linear regression model.


## Key Insights

* Present price has the strongest positive influence on resale value.
* Newer vehicles generally have higher selling prices.
* Higher mileage negatively impacts resale value.
* Ownership history slightly reduces market price.


## How to Run This Project

1. Clone the repository:

   
   git clone https://github.com/archana03-sudo/CodeAlpha_Car_Price_Prediction.git
   

2. Install required dependencies:

   pip install -r requirements.txt
  

3. Open the notebook:
   
   jupyter notebook
