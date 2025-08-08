# 🛒 Retail Sales Forecasting

## 📌 Project Overview
This project focuses on **predicting weekly sales for each store** using various time series forecasting techniques.  
The goal is to identify the best-performing model for accurate sales predictions, helping businesses in **inventory management**, **staff planning**, and **promotional strategies**.

---

## 🎯 Objective
- Predict **weekly store sales**.
- Compare different forecasting models.
- Identify trends, seasonality, and anomalies.

---

## 📂 Dataset
- **Source:** [Kaggle / Company-provided]  
- **Features:**  
  - `Store` – Store ID  
  - `Date` – Week start date  
  - `Weekly_Sales` – Sales in USD  
  - Other potential predictors like holidays and promotions  

---

## 🔍 Approach

### **1. Data Understanding & Preprocessing**
- Handled missing values
- Converted date formats
- Grouped data by `Store` and `Date`
- Performed exploratory data analysis (EDA)

### **2. Baseline Models**
- **Naive Forecasting** – Last observed value as next prediction
- **Moving Average** – Smoothed predictions

### **3. Advanced Models**
- **ARIMA** – Captured trends & seasonality  
- **Facebook Prophet** – Automated handling of seasonality & holidays  

---

## 📊 Visualization
Used **Python** libraries to:
- Plot trends & seasonal patterns
- Compare actual vs predicted sales
- Evaluate error metrics

---

## 🏆 Results
- Prophet outperformed other models with **~30% better accuracy** compared to baseline.
- Clear weekly and yearly seasonality patterns were identified.

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Statsmodels (ARIMA)
- Facebook Prophet
- Jupyter Notebook

---

## 📌 Key Learnings
- Importance of baselines before advanced models
- How seasonality impacts retail sales
- Prophet’s strengths in handling irregular events

---

## 📄 Future Improvements
- Include external factors like weather & promotions
- Try machine learning approaches (XGBoost, LSTM)
- Build a dashboard in Tableau for real-time monitoring

---

## 📬 Contact
**Author:** Mathu Malathi G  
📧 Email: mathumalathig@gmail.com  
🔗 LinkedIn: www.linkedin.com/in/mathu-malathi-gopal 
