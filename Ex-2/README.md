# 🏦 Loan Amount Prediction using Linear Regression

This project aims to predict the loan amount approved for applicants based on various demographic and financial attributes using **Linear Regression**. The model is built using a dataset sourced from [Kaggle](https://www.kaggle.com/datasets/phileinsophos/predict-loan-amount-data), and evaluation is done using performance metrics like MAE, MSE, RMSE, and R².

---

## 📁 Dataset

The dataset contains numerical and categorical features related to loan applicants, such as:
- `ApplicantIncome`
- `CoapplicantIncome`
- `LoanAmount`
- `Loan_Amount_Term`
- `Credit_History`
- And others...

---

## 🧪 Experiment 2 - Objectives

- Build a Linear Regression model to predict `LoanAmount`.
- Preprocess and visualize numerical features.
- Evaluate model performance using K-Fold Cross Validation.
- Visualize prediction results.

---

## ⚙️ Technologies Used

- Python 3.x
- Jupyter / Google Colab
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## 📊 Metrics (5-Fold Cross Validation)

| Metric | Average Value |
|--------|----------------|
| MAE    | 21799.92       |
| MSE    | 1000635153.57  |
| RMSE   | 31632.82       |
| R²     | 0.5652         |

---

## 📈 Visualizations

- Distribution plots of numerical features
- Actual vs Predicted values (scatter plot)
- Residual plots

---

## 🔁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Bloomberg890/ML_Laboratory.git
   cd ML_Laboratory.git/Ex-2
