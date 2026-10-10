# House Price Prediction Using Linear Regression

## 1. Project Overview

This project predicts median house values using the California Housing dataset and a Linear Regression model.

## 2. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

## 3. Dataset

The project uses the California Housing dataset available through Scikit-learn. It contains numerical housing and geographic features, with `MedHouseVal` as the target variable.

The target is expressed in units of $100,000.

## 4. Methodology

1. Loaded and explored the dataset.
2. Checked missing values and duplicate rows.
3. Selected input features and the target variable.
4. Created additional household-related ratio features.
5. Split the data into 80% training and 20% testing sets.
6. Applied feature scaling using StandardScaler.
7. Trained a Linear Regression model.
8. Compared it with a mean-prediction baseline.
9. Evaluated performance using MAE, RMSE and R².
10. Performed five-fold cross-validation on the training data.
11. Created actual-versus-predicted, residual and feature importance charts.
12. Saved the trained pipeline and evaluation results.

## 5. Model Evaluation

The project reports MAE, RMSE, R² and five-fold cross-validation RMSE.

Actual performance values should be added after running the notebook.

## 6. Visualizations

- Actual vs Predicted House Values
- Residual Plot
- Feature Importance using Standardized Coefficients

## 7. Limitations

- Linear Regression assumes a linear relationship between input features and the target.
- The dataset may not represent housing markets outside California.
- Important factors such as property condition and current market changes may not be fully represented.
- Target values are capped at approximately $500,000.
- Correlated features can affect coefficient interpretation.
- Predictions are estimates, not exact market prices.

## 8. How to Run

1. Open the notebook in Google Colab.
2. Execute all cells in order.
3. Review evaluation metrics and charts.
4. Download generated files if needed.

## 9. Conclusion

This project demonstrates feature engineering, scaling, model training, baseline comparison, cross-validation, evaluation and limitation analysis using Python and Scikit-learn.
