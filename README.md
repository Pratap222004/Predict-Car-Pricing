# 🚗 Car Price Prediction Using Machine Learning

## 📌 Overview
This project predicts the selling prices of used cars by analyzing historical data and identifying the key factors influencing pricing trends.  
It uses a **Linear Regression** model, with proper data cleaning, preprocessing, and feature engineering to ensure accurate predictions.

---

## 🎯 Objectives
- Develop a machine learning model for accurate car price prediction.
- Identify significant features impacting car prices.
- Provide insights through clear visualizations.

---

## 📂 Dataset
- **Source:** [Kaggle – Quikr Car Dataset]
- **Features:**.
  - `Name` – Car name & model.
  - `Year` – Year of manufacture.
  - `Company` – Car brand.
  - `Kms_driven` – Total kilometers driven.
  - `Fuel_type` – Petrol/Diesel/CNG.
  - `Price` – Selling price (Target).

---

## 🛠 Methodology
1. **Data Collection** – Downloaded from Kaggle in CSV format.
2. **Data Cleaning** – Removed duplicates, irrelevant rows, and handled missing values.
3. **Data Preprocessing** – One-Hot Encoding for categorical features; normalization of numerical data.
4. **Model Training** – Implemented **Linear Regression** to capture linear feature-price relationships.
5. **Model Evaluation** – Measured performance using **R² score**.

---

## 📊 Results
- **R² Score:** `0.89` (Strong predictive power)
- **Key Insight:** `Kms_driven` negatively impacts price — higher mileage reduces car value.
- **Visualizations:**
  - Box plots showing price distribution by company.
  - Scatter plots highlighting correlations between features and price.

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Model:** Linear Regression

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Car_Price_Prediction.ipynb
