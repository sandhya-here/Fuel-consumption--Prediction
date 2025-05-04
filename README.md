# 🔋 Fuel Consumption Prediction Project

This project predicts the **fuel consumption** of vehicles using a dataset containing technical specifications like weight, engine capacity, energy consumption, and fuel type. The goal is to build a regression model that accurately estimates fuel usage (L/100 km).

---

## 📁 Files Included

- `Reduced-Data.xlsx` or `Reduced-Data.csv` — Raw structured data file
- `Fuel_Consumption_Prediction_Structured_Test.ipynb` — Jupyter notebook for model training
- `README.md` — Project overview and usage instructions

---

## 🔧 Technologies Used

- **Python 3**
- **Pandas** — Data handling
- **NumPy** — Numeric operations
- **Matplotlib / Seaborn** — Visualization
- **Scikit-learn** — ML models and preprocessing

---

## 📊 Features

- Loads structured vehicle data (CSV/Excel)
- Cleans and preprocesses the dataset
- Encodes categorical variables
- Applies feature scaling
- Splits data into training and testing sets
- Trains a Linear Regression model
- Evaluates using RMSE and R² score
- Visualizes actual vs predicted results

---

## ▶️ How to Run

### 1. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn fsspec openpyxl
