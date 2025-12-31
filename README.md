AI-Driven Inventory Management System
📌 Overview

This project is an AI-driven Inventory Management System designed to forecast product demand and assist businesses in making better inventory decisions.
Using historical retail sales data, the system predicts future demand, identifies low-stock risks, and recommends reorder quantities.

The project demonstrates an end-to-end Machine Learning workflow, from data cleaning to business insights.

🎯 Problem Statement

Retail businesses often face challenges such as:

Overstocking (high holding cost)

Stock-outs (lost sales)

This project uses Machine Learning to:

Forecast demand

Detect low-stock products

Suggest reorder quantities based on predictions

🛠 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Tools: Jupyter Notebook, Git, GitHub

ML Model: Linear Regression, Random Forest Regressor

📂 Project Structure
Inventory_Management/
│
├── data/
│   ├── retail_store_inventory.csv        # Raw dataset
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── EDA.ipynb
│   ├── feature_engineering.ipynb
│   ├── model_training.ipynb
│   └── inventory_insight.ipynb
│
├── .gitignore
├── README.md

🔄 Project Workflow
1️⃣ Data Cleaning

Handled missing values

Removed duplicates

Converted date columns

Validated sales and inventory values

2️⃣ Exploratory Data Analysis (EDA)

Sales trends over time

Monthly demand analysis

Top-selling products

Inventory vs sales relationship

Correlation analysis

3️⃣ Feature Engineering

Time-based features (day, month, weekday)

Lag features (previous demand)

Rolling averages for trend capture

Categorical encoding

4️⃣ Model Training

Trained Linear Regression as a baseline model

Trained Random Forest Regressor for non-linear patterns

Evaluated models using RMSE and R² Score

Selected Random Forest as the final model

5️⃣ Inventory Insights

Predicted product demand

Identified low-stock products

Calculated reorder quantities

Generated actionable business insights

📊 Results

Random Forest outperformed Linear Regression

Lag and rolling features significantly improved demand prediction

System successfully identified low-stock risks and reorder needs

💡 Key Learnings

Importance of feature engineering in time-series problems

Handling real-world retail data

Translating ML predictions into business decisions

Version control best practices using Git & GitHub

🚀 Future Improvements

Add time-series models (ARIMA / LSTM)

Build a Flask-based web dashboard

Automate daily demand prediction

Deploy the model as a REST API

👤 Author

Jay Mistry
BSc IT | Aspiring AI/ML Engineer

🔗 GitHub: https://github.com/Mistryjay20

🔗 LinkedIn: (Add your LinkedIn profile link here)

📌 Acknowledgements

Dataset sourced from Kaggle

Inspired by real-world retail inventory challenges
