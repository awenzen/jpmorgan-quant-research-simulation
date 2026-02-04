# J.P. Morgan Quantitative Research Simulation 
> *This repository contains financial modeling and risk analysis developed during the J.P. Morgan Quant Research Virtual Experience.*

## 📈 Project Overview
This project covers two major workstreams: **Commodities Trading** and **Retail Credit Risk**. 

---

## 📂 Task 1: Natural Gas Price Prediction
### Objective
To estimate future gas prices using historical data, accounting for long-term trends and seasonal fluctuations.

### Methodology
- **Linear Regression:** Captures the general upward or downward price trend over time.
- **Seasonal Adjustments:** Calculates "monthly adders" to account for price spikes in winter and dips in summer.



---

## 📂 Task 2: Storage Contract Valuation
### Objective
Calculate the fair value of a gas storage contract.
- **Logic:** Valuation = (Sale Price - Purchase Price) - Storage Costs - Injection/Withdrawal Fees.

---

## 📂 Task 3 & 4: Credit Risk PD Model
### Objective
Predict the **Probability of Default (PD)** for borrowers to estimate portfolio expected loss.

### Model Performance
I utilized a **Logistic Regression** model using variables like FICO score and Loan-to-Income (LTI) ratio. 
- **Key Metric:** Used the AUC-ROC curve to validate model accuracy.



---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn)
- **Matplotlib/Seaborn** (Data Visualization)
