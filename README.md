# Health-Cost-Prediction
A linear regression model to predict healthcare expenses based on age, BMI, smoking status, and other features.


# 💸 Health Cost Prediction using Linear Regression

This project builds a **Linear Regression model** to predict individual healthcare costs based on personal attributes like age, sex, BMI, smoking status, and region. Built entirely in **Google Colab** using **scikit-learn**.

---

## 🔍 Problem Statement

Given a dataset with features like:
- Age
- Sex
- BMI
- Children
- Smoker (yes/no)
- Region

💡 Predict the `charges` (annual health insurance cost)

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn (LinearRegression)
- Matplotlib & Seaborn (for plots)
- Google Colaboratory

---

## 🔧 Model Details

- Data cleaned and preprocessed (categorical → numerical)
- Feature-target split (80% train, 20% test)
- Applied `LinearRegression()` from scikit-learn
- Evaluated using **Mean Absolute Error (MAE)**

---

## 📈 Sample Output

python
📊 Mean Absolute Error on test set: $3217.45


📦 health-cost-prediction
├── health_cost_prediction_linear_regression.ipynb  # Main notebook
├── insurance.csv (if uploaded separately)
└── README.md

