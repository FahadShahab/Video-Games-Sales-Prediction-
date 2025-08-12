# 🎮 Video Game Sales Prediction  

**Predicting global video game sales using Multiple Linear Regression, Random Forest, and SVM (RBF kernel), with a focus on how preprocessing choices affect performance.**  

---

## 📌 Project Overview  
This project explores the prediction of **global video game sales** based on historical data, applying three regression algorithms:  
- **Multiple Linear Regression (MLR)** — for interpretable, assumption-based modeling  
- **Random Forest Regression (RFR)** — for robust, non-linear prediction without scaling requirements  
- **Support Vector Machine (SVM) with RBF kernel** — for capturing complex non-linear patterns in scaled datasets  

Through **Exploratory Data Analysis (EDA)**, **feature engineering**, and **data preprocessing** (scaling, outlier removal, train-test variations), the project evaluates how different data treatments influence each model’s accuracy.  

---

## 🛠 Tech Stack  
- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Techniques:** EDA, Feature Engineering, Outlier Removal, Feature Scaling, Model Evaluation  
- **Evaluation Metrics:** RMSE, MAE  

---

## 📊 Key Findings  
- **Random Forest** performed best on **raw, unscaled data**.  
- **SVM (RBF)** excelled on **scaled datasets**.  
- **Multiple Linear Regression** achieved the **lowest error** after **scaling and outlier removal**.  

---

## 📂 Dataset Variants  
1. **Raw Data** (70:30 split) — No scaling or outlier removal  
2. **Scaled Data** (70:30 split) — StandardScaler applied  
3. **Scaled + Outlier Removal** (70:30 split) — IQR method for outlier removal  
4. **Scaled + Outlier Removal** (80:20 split) — Larger training set for improved learning  

---
