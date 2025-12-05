# 🛒 Walmart Sales Forecasting Project

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-1.5-brightgreen?logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange?logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-0.12-blueviolet?logo=seaborn&logoColor=white)  

---

## 🔹 Project Overview
This project analyzes **Walmart store sales data** to uncover **trends, seasonal patterns, and department/store insights**, with the ultimate goal of **forecasting future sales**.  

> “Turning raw data into actionable business intelligence” 📊✨  

---

## 🎯 Key Objectives
- Clean & preprocess Walmart sales data 🧹  
- Detect & handle **outliers** and missing values ⚠️  
- Perform **univariate, bivariate, and multivariate analysis** 🔍  
- Explore **seasonal trends & holiday impacts** 🗓️  
- Engineer meaningful features for enhanced analysis 💡  
- Prepare dataset for **predictive sales forecasting** 🤖  

---

## 🗂 Tasks Performed

### 1️⃣ Data Cleaning & Preprocessing
- Filled missing numeric values with **median**  
- Filled missing markdowns with **mean**  
- Converted `Date` to **datetime**  
- Removed duplicates and reset index ✅  

### 2️⃣ Outlier Detection & Treatment
- Used **Boxplots** and **IQR method**  
- Preserved **holiday-week spikes** as legitimate business outliers  

### 3️⃣ Exploratory Data Analysis (EDA)
- **Univariate:** Weekly Sales, Store Type, Temperature, Fuel Price, CPI, Unemployment  
- **Bivariate:** Weekly Sales vs Temperature/Fuel Price/Store Type/Holiday Flag  
- **Multivariate:** Correlation heatmap, Store Size, Markdown impact, Holiday effects  
- **Time Series:** Weekly & monthly trends, seasonal peaks, department demand  

### 4️⃣ Feature Engineering
- Created:  
  - `discount_effect` = sum of all markdowns 💰  
  - `normalized_sales` = Weekly_Sales / Store Size 📏  
  - `is_peak_season` = True if month in Nov/Dec 🎄  
  - `Year`, `Month`, `Week` from Date 🗓️  
- Filtered **peak-season high sales transactions**  
- Calculated **revenue potential per store**  

---

## 📊 Key Visualizations
- Histograms & KDE plots 📈  
- Boxplots for outlier detection & comparisons 📦  
- Scatterplots for variable relationships 🌐  
- Heatmaps for correlation & department-season analysis 🔥  
- Line plots for time series trends 🕰️  
- Barplots for top departments and stores 🏆  

---

## 💻 Tools & Libraries
- Python 3.x 🐍  
- pandas, numpy 🧮  
- matplotlib, seaborn 🎨  
- scikit-learn, statsmodels 🤖  
- Jupyter Notebook 📓  

---

## 🚀 Business Insights
- Peak season (Nov–Dec) drives **highest sales spikes** 🎉  
- Top stores & departments contribute significantly to revenue 💸  
- Markdown discounts influence sales differently for **holiday vs non-holiday weeks**  
- Revenue potential can be estimated as `Weekly_Sales * 52` 💰  

---

## 🔮 Future Scope
- Implement **predictive sales forecasting** using ML models (ARIMA, Prophet, regression) 🤖  
- Build **interactive dashboards** for store managers 📊  
- Extend analysis to **promotions & inventory optimization**  

---
