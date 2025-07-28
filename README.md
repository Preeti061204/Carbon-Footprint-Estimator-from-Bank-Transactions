# Carbon-Footprint-Estimator-from-Bank-Transactions

## 📘 Project Overview
This project estimates the carbon footprint (CO₂e) of users by analyzing their bank transaction data. Firstly, transactions were categorized and then spending behavior was analyzed, dividing users into tiers based on monthly CO₂e levels (Good, Neutral, Bad). Machine learning models were then trained to predict CO₂ emissions based on transaction amount, category, and subcategory.

## 🎯 Objectives
- Categorize transactions and calculate estimated CO₂ emissions
- Segment users into CO₂e tiers for eco-impact analysis
- Train ML models to predict CO₂ emissions from new transactions
- Provide an interactive tool for real-time CO₂e estimation

## 🛠 Tools & Technologies Used
- Languages: Python
- Libraries:
  - Pandas, NumPy: Data Processing
  - Matplotlib, Seaborn: Data visualization
  - Scikit-learn: Machine Learning models & evaluation
  - Joblib: Model Serialization
- Excel: Data annotation and analysis
- Environment: Jupyter Notebook
 
## 🚀 Key Features
- Cleaned and categorized synthetic bank transaction dataset
- Tiering system based on monthly CO₂ emission levels
- Multiple regression models with comparison (R², MAE, RMSE, Max Error)
- Residual plots, predicted vs. actual plots, feature importance charts
- Interactive script to estimate CO₂e from user input (amount, category, subcategory)
