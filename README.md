# 📌 Hierarchical Bayesian Logistic Regression for EUR/USD Market Prediction
**Advanced Bayesian Data Analysis Project**

---

## 📖 Overview
This project explores **Hierarchical Bayesian Logistic Regression** for predicting **EUR/USD market movements** based on technical indicators. It compares standard and hierarchical models, evaluates prior sensitivity, and analyzes exchangeability assumptions using **Bayesian inference techniques**.

---

## 📊 Key Features
✔ **Bayesian Logistic Regression** using the `brms` package  
✔ **Hierarchical Modeling** to capture temporal dependencies (hour & day-based grouping)  
✔ **Model Comparison** using **ELPD** (Expected Log Predictive Density) and **LOOIC** (Leave-One-Out Information Criterion)  
✔ **Prior Sensitivity Analysis** to assess the influence of different priors  
✔ **Posterior Predictive Checks (PPCs)** to validate model consistency  
✔ **Exchangeability Analysis** to test if hierarchical groupings affect inference  

---

## 📎 Code & Data Availability
- **📂 GitHub Repository (Code):** [Project Repository](https://github.com/apumrk/abda-project)
- **📊 Dataset Source:** [Kaggle: EUR/USD Forex Dataset](https://www.kaggle.com/datasets/rsalaschile/forex-eurusd-dataset)

Users can access the dataset and scripts for further analysis and modifications.

---

## 🛠 Requirements
### **R Libraries Needed**
To run this project, install the following **R** packages:
```r
install.packages(c("brms", "ggplot2", "loo", "dplyr"))
