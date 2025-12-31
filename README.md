# AI-Driven Inventory Management System

## Overview
This project implements an AI-driven inventory management system that forecasts product demand using historical retail sales data.  
The goal is to help businesses reduce stock-outs and overstocking by making data-driven inventory decisions.

The project demonstrates a complete **machine learning pipeline**, from data preprocessing to actionable inventory insights.

---

## Problem Statement
Retail inventory planning is challenging due to fluctuating demand.  
Manual estimation often leads to excess inventory or missed sales.

This system addresses the problem by:
- Forecasting future demand
- Identifying low-stock risk
- Recommending reorder quantities

---

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## Dataset
- Source: Kaggle (Retail Store Inventory Forecasting Dataset)
- Data includes:
  - Date
  - Product ID
  - Category
  - Units Sold
  - Inventory Level
  - Price
  - Discount

---

## Project Structure

- Inventory_Management/
- │
- ├── data/
-- │   └── retail_store_inventory.csv        # Raw dataset only
-- │
- ├── notebooks/
-- │   ├── data_cleaning.ipynb
-- │   ├── EDA.ipynb
-- │   ├── feature_engineering.ipynb
-- │   ├── model_training.ipynb
-- │   └── inventory_insight.ipynb
- │
- ├── .gitignore
- ├── README.md


---

## Methodology

### 1. Data Cleaning
- Handled missing values
- Removed duplicates
- Converted date columns
- Validated sales and inventory data

### 2. Exploratory Data Analysis (EDA)
- Sales trend analysis
- Seasonal demand patterns
- Category-wise sales distribution
- Inventory vs sales analysis

### 3. Feature Engineering
- Time-based features (day, month, weekday)
- Lag features to capture historical demand
- Rolling averages to smooth demand trends
- Encoding categorical variables

### 4. Model Training
- Linear Regression used as a baseline
- Random Forest Regressor used for final model
- Model evaluation using RMSE and R² score

### 5. Inventory Insights
- Demand prediction for each product
- Low-stock identification
- Reorder quantity calculation

---

## Results
- Random Forest achieved better performance than Linear Regression
- Lag and rolling features significantly improved forecasting accuracy
- The system successfully generated actionable inventory recommendations

---

## Key Learnings
- Importance of feature engineering in demand forecasting
- Handling real-world retail data
- Translating ML predictions into business insights
- Using GitHub for version control and project documentation

---

## Future Enhancements
- Implement time-series models (ARIMA / LSTM)
- Build a web-based dashboard
- Deploy model as an API
- Automate inventory alerts

---

## Author
**Jay Mistry**  
BSc IT | Aspiring AI/ML Engineer  

GitHub: https://github.com/Mistryjay20/Inventory_Management  
LinkedIn: www.linkedin.com/in/jaykumar-mistry-7a81a2325

---
