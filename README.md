# Real Estate Price Prediction using Polynomial Regression

## Overview
This project focuses on predicting **house prices per unit area** based on various real estate features such as house age, proximity to MRT stations, and number of convenience stores.  
We utilize **Polynomial Regression** to capture nonlinear relationships between the features and the target variable, and compare its performance with **Simple Linear Regression**.

---

##  Dataset Description
The dataset contains the following columns:

| Column | Description |
|:--------|:-------------|
| X1 | Transaction Date |
| X2 | House Age (years) |
| X3 | Distance to the Nearest MRT Station (meters) |
| X4 | Number of Convenience Stores nearby |
| X5 | Latitude |
| X6 | Longitude |
| Y | House Price of Unit Area |

---

##  Project Workflow

### 1️ Import All Necessary Libraries
- Import essential Python libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn`.

### 2️ Check Out the Data
- Load and inspect the dataset.
- Check data types, missing values, and perform descriptive statistics.

### 3️ Exploratory Data Analysis (EDA)
- Visualize relationships using scatter plots and heatmaps.
- Analyze correlation between features and the target variable.

### 4️ Training a Polynomial Regression Model
- Generate polynomial features using `PolynomialFeatures` from `sklearn.preprocessing`.
- Fit the model on the training data and predict on the test data.

### 5️ Predicting Test Data
- Use the trained model to predict house prices on unseen test data.

### 6️ Evaluating the Model
- Compute evaluation metrics such as:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**

### 7️ Compare to the Simple Linear Regression
- Train a linear regression model for comparison.
- Observe performance differences between linear and polynomial models.

### 8️ Adjusting Model Parameters
- Tune the polynomial degree to minimize RMSE.
- Use cross-validation for robust evaluation.

### 9️ Plot Polynomial Degree vs RMSE
- Plot RMSE against polynomial degrees to identify the optimal model complexity.

---

## Results
- Polynomial Regression shows improved performance over Linear Regression.
- The relationship between degree of polynomial and RMSE is visualized to select the best degree.

---

