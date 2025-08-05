# Predicting Home Values Using Regression Models – Boston Housing Dataset

This project explores and compares the performance of four regression models to predict the **median value of owner-occupied homes** (`MEDV`) using the classic **Boston Housing dataset**.

## Objective

To build, evaluate, and compare the performance of:
- Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor

…in predicting home values based on features like crime rate, number of rooms, property tax, etc.

---

## Summary of Findings

- **Polynomial Regression** performed best:
  - **R² Score**: 0.87 (highest)
  - **MSE**: 10.84 (lowest)
  - **RMSE**: 0.4103
  - **MAE**: 2.44

- **Random Forest** was a close second:
  - **R²**: 0.83
  - **MSE**: 13.83
  - **MAE**: 2.50

- **Linear Regression** and **Decision Tree** underperformed:
  - Linear Regression: lowest R² (0.71), highest MSE (23.60)
  - Decision Tree: R² = 0.73, MAE = 3.08, MSE = 22.34

---

##  Key Techniques

-  **Data Preprocessing**:
  - Standardized all numerical features using `StandardScaler`
  - Applied **Winsorization** to reduce the impact of outliers

- **Model Evaluation Metrics**:
  - R² Score
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)

---

##  Next Steps / Improvements

- Tune the hyperparameters of the Polynomial and Tree-based models (e.g., degree, max_depth)
- Apply **cross-validation** to improve model robustness
- Engineer additional features (e.g., interaction terms, different polynomial degrees)
- Explore advanced models (e.g., Gradient Boosting, SVR)

---

## Files

- `boston.csv`:Dataset used
- `Boston_Housing_Regression_Models.ipynb`:**Full analysis and model Colab notebook name**
- `README.md`: Project description and results
