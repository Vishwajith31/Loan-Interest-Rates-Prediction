# Loan Interest Rate Prediction (Capstone Project)  

## 📌 Overview  
This project applies **multiple regression analysis** to predict loan interest rates based on borrower and loan attributes.  
It was completed as part of the *DeepLearning.AI Python for Data Analytics Specialisation*.  

The goal is to demonstrate:  
- End-to-end data preprocessing and feature engineering  
- Applying **Multiple Linear Regression** with Scikit-learn & Statsmodels  
- Evaluating regression performance using metrics such as **R², MAE, and RMSE**  
- Interpreting which borrower/loan factors most influence interest rates  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, NumPy, Scikit-learn, Statsmodels)  
- **Jupyter Notebook** for analysis and visualization  

---

## 📂 Project Structure  
``` bash

Loan-Interest-Rates-Prediction/
├── data/
│ └── LoanData.csv # Dataset (Bondora P2P Loans)
├── notebooks/
│ └── loan_interest_prediction.ipynb # Main Jupyter Notebook
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .gitignore # Ignored files

```
---

## 📊 Dataset  
The dataset used in this project comes from **Bondora P2P Loans** on Kaggle:  
👉 [Bondora P2P Loan Data (LoanData.csv)](https://www.kaggle.com/datasets/marcobeyer/bondora-p2p-loans?select=LoanData.csv)  

It includes borrower and loan attributes such as:  
- Loan Amount  
- Credit Score  
- Income  
- Employment Type  
- Purpose of Loan  
- Interest Rate (target variable)  

📌 Note: The raw CSV (~62MB) is **not included in this repository** due to GitHub’s file size recommendations. Please download it from Kaggle and place it in the `data/` folder before running the notebook.  

---

## 🚀 Workflow  
1. **Data Preprocessing** – handle missing values, encode categorical variables, scale features  
2. **Exploratory Data Analysis (EDA)** – identify correlations and feature importance  
3. **Model Training** – Multiple Linear Regression with OLS regression analysis  
4. **Evaluation** – Model achieved **R² ≈ 0.60** on test data  

---

## 📈 Results  
- Multiple Linear Regression was applied to predict loan interest rates  
- OLS results: **R² ≈ 0.602**, showing moderate predictive power  
- Identified key features influencing loan interest rates  

---

## 🔗 Future Improvements  
- Experiment with **regularization techniques** (Ridge, Lasso)  
- Explore **non-linear models** (XGBoost, RandomForestRegressor)  
- Deploy as a simple web app for interactive predictions  

---

## 📎 Author  
👤 **Vishwajith Somarampet**  
- [GitHub](https://github.com/Vishwajith31)  
- [LinkedIn](https://www.linkedin.com/in/vishwajithsoma31/?trk=opento_sprofile_topcard)  
