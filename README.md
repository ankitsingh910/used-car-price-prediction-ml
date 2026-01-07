# used-car-price-prediction-ml
Machine learning project to predict used car selling prices in the Indian market using EDA, feature engineering, and regression models, with Random Forest achieving high accuracy.

## 📌 Project Overview
Predicting the selling price of used cars is a critical challenge in the automotive and resale market. This project aims to build a robust and accurate **machine learning model** to predict used car prices in the **Indian market** using historical data and advanced regression techniques.

The project covers the complete data science pipeline including **data collection, preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation**.

---

## 🎯 Objective
- Predict the selling price of used cars with high accuracy
- Reduce pricing uncertainty for sellers and buyers
- Help businesses optimize pricing strategies
- Understand key factors influencing car resale value

---

## 🗂 Dataset
- Source: Web-scraped from **CarDekho**
- Rows: **15,411**
- Columns: **14**

### Key Features
- `vehicle_age`
- `km_driven`
- `fuel_type`
- `transmission_type`
- `mileage`
- `engine`
- `max_power`
- `seats`
- `seller_type`
- `model`
- `selling_price` (Target Variable)

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights from EDA:
- Most cars are less than 10 years old
- Selling price is right-skewed with premium car outliers
- Strong positive correlation between:
  - Selling price & max power
  - Selling price & engine capacity
- Automatic cars generally have higher resale value
- Vehicle age and selling price are negatively correlated

---

## ⚙️ Data Preprocessing
- Removed duplicate rows
- Dropped redundant columns
- Outlier handling using IQR method
- Square root transformation to reduce skewness
- One-Hot Encoding for categorical variables
- Feature scaling using `StandardScaler`
- Train-Test split: **80:20**

---

## 🧠 Machine Learning Models Used
| Model | Test Accuracy | R² Score |
|------|--------------|----------|
| Linear Regression | 85.2% | 0.87 |
| Elastic Net | 85.3% | 0.88 |
| Decision Tree Regressor | 88.5% | 0.90 |
| **Random Forest Regressor** | **90.2%** | **0.93** |

✔ **Random Forest Regression** performed best and was selected as the final model.

---

## 📊 Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score
- MAPE (Mean Absolute Percentage Error)
- Accuracy = `100 - MAPE`

---

## 🏆 Results
- Final model achieved **90.2% accuracy**
- High generalization with minimal overfitting
- Predicted values closely overlap actual prices

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 🚀 How to Run
```bash
git clone https://github.com/your-username/used-car-price-prediction-ml.git
cd used-car-price-prediction-ml
fcm-ggeu-xsm
