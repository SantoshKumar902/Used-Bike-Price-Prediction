# 🏍️ Used Bike Price Prediction | Data Analysis & Machine Learning Project

This project focuses on **predicting the resale price of used bikes** using data analysis, feature engineering, and machine learning models. It includes everything from data cleaning to visualization and predictive modeling.

---

## 📁 Project Structure

Used-Bike-Price-Prediction/ <br>
├── # Dataset used (bikes.csv) <br>
├──  Colab notebook/ # Main notebook <br>
│ └── Analyzed Dataset (Solution).ipynb <br>
├── images/ # Visualizations and plots <br>
│ ├── heatmap.png <br>
│ ├── cc_distribution.png <br>
│ └── price_vs_year.png <br>
└── README.md # Project overview


---

## 📊 Problem Statement

Given a dataset of used bikes containing features like model, year, mileage, power, brand, ownership, and kilometers driven — the goal is to **predict the price** of the used bikes accurately.

---

## 📌 Key Tasks Covered

✅ Data Cleaning & Preprocessing  
✅ Feature Engineering (Bike Age, CC Extraction, Encoding)  
✅ Exploratory Data Analysis (EDA)  
✅ Visualizations (Histograms, Heatmaps, Boxplots)  
✅ Model Building (Linear, Tree, and Ensemble Models)  
✅ Evaluation (MAE, RMSE, R² Score)

---

## 🔍 Dataset Overview

The dataset includes:

- **model_name** – Full name of the bike
- **model_year** – Year of manufacture
- **kms_driven** – Distance driven in kilometers
- **owner** – Ownership type (first, second, etc.)
- **location** – City of registration
- **mileage** – Mileage of the bike
- **power** – Engine power in bhp
- **cc** – Extracted engine capacity
- **price** – Selling price (target)

---

## 🧠 Feature Engineering

- **CC extraction** from `model_name`
- **Age of bike** from `model_year`
- **Location encoding** using LabelEncoder
- **Power-to-weight ratio** (where possible)

---

## 📈 Some Visualizing Samples

### 🔹 Brand-wise Split

- <a href="https://github.com/SantoshKumar902/Used-Bike-Price-Prediction/blob/main/Brand%20Wise%20Split%20of%20Bike.png">Brand Split</a>

### 🔹 Top 15 most Frequent Bike CC Categories 

- <a href = "https://github.com/SantoshKumar902/Used-Bike-Price-Prediction/blob/main/Top%2015%20Most%20Frequent%20Bike%20CC%20Categories.png">CC Categories</a>

### 🔹 Actual vs Predicted Price

- <a href = "https://github.com/SantoshKumar902/Used-Bike-Price-Prediction/blob/main/Actual%20vs%20Predicted%20Price.png">Price</a>

---

## 🤖 Model Building

Machine Learning models trained:

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

### 📊 Evaluation Metrics:
| Model                | MAE     | RMSE    | R² Score |
|---------------------|---------|---------|----------|
| Linear Regression   | 12800   | 18600   | 0.72     |
| Decision Tree       | 6200    | 9100    | 0.91     |
| Random Forest       | 5100    | 8500    | 0.94     |

---

## 📦 Libraries Used
- pandas, numpy

- matplotlib, seaborn

- sklearn

- re, warnings

##  🎯 Insights & Findings
- Most bikes in the dataset are from 2016–2020

- Royal Enfield, Yamaha, and Bajaj dominate the second-hand market

- First-owner bikes tend to have higher resale value

- Power and CC have positive correlation with price

 # 🏁 Conclusion
This project demonstrates the complete life cycle of a real-world data science and machine learning project — from raw data to an intelligent model that predicts prices.
