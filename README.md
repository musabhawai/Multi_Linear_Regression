# Multi_Linear_Regression

## 📌 Overview
This repository contains multiple small projects that demonstrate the use of *Multiple Linear Regression* for different prediction problems:
1. *Predicting Home Price* – Using multiple features such as area, number of bedrooms, and number of bathrooms.
2. *Predicting Salary* – Based on factors like years of experience and test scores.
3. *Predicting Home Price with Dummy Variables* – Incorporating categorical features such as city.
4. *Predicting Car Price with Dummy Variables* – Considering categorical factors like car model and mileage.

## 📖 About Multiple Linear Regression
Multiple Linear Regression is an extension of *Linear Regression* that uses *two or more independent variables* to predict a continuous target variable.  
The model fits a linear equation of the form:

\[
y = b_0 + b_1x_1 + b_2x_2 + ... + b_nx_n
\]

Where:
- \( y \) is the predicted value  
- \( x_1, x_2, ..., x_n \) are input features  
- \( b_0 \) is the intercept  
- \( b_1, b_2, ..., b_n \) are coefficients  

This method helps capture the combined effect of multiple predictors on the target variable.

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Predicting Home Price
- *Goal*: Estimate home prices based on multiple numerical features.
- *Process*:
  - Load and clean dataset
  - Train Multiple Linear Regression model
  - Predict prices for given inputs

### 2️⃣ Predicting Salary
- *Goal*: Estimate salaries based on experience and test scores.
- *Process*:
  - Load dataset
  - Train model
  - Predict salary for specific inputs

### 3️⃣ Predicting Home Price with Dummy Variables
- *Goal*: Include categorical features such as city in the model.
- *Process*:
  - Use one-hot encoding for categorical data
  - Train and predict

### 4️⃣ Predicting Car Price with Dummy Variables
- *Goal*: Use categorical data like car model and mileage to improve prediction.
- *Process*:
  - Convert categorical variables into dummy variables
  - Train and predict
