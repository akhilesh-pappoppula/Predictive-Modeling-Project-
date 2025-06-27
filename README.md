# 🎬 OTT First-Day Viewership Prediction - Linear Regression

## 📄 Project Overview

This project involves building a predictive model to identify the key factors that drive **first-day content viewership** for an OTT (Over-The-Top) platform called **ShowTime**. The project was part of my **Post Graduate Program in Data Science (PGPDS.O. MAR25.A)**.

The objective was to assist ShowTime in improving their content performance through data-driven insights.

---

## 🎯 Problem Statement

With the increasing shift from traditional television to OTT platforms, understanding the factors that influence first-day content viewership is critical. The goal is to:

✅ Identify the driving factors for first-day viewership  
✅ Build a reliable regression model to predict viewership  
✅ Provide actionable business recommendations  

---

## 🗃 Dataset

The dataset includes:

- `visitors`: Average number of visitors (in millions)  
- `ad_impressions`: Number of ad impressions (in millions)  
- `major_sports_event`: Presence of major sports events on release day (Yes/No)  
- `genre`: Genre of the content  
- `dayofweek`: Day of content release  
- `season`: Season of release  
- `views_trailer`: Number of trailer views (in millions)  
- `views_content`: First-day content views (target variable, in millions)  

---

## 🔧 Key Steps

- Exploratory Data Analysis (EDA)  
- Univariate & Bivariate Analysis  
- Correlation Analysis  
- Data Preprocessing & Encoding  
- Model Building: Linear Regression (OLS)  
- Model Evaluation & Assumptions Testing  
- Business Insights & Recommendations  

---

## 📊 Model Performance

| Metric                | Training Set | Test Set |
|----------------------|--------------|----------|
| R²                   | 78.9%        | 76.2%    |
| RMSE                 | 0.0488       | 0.0511   |
| MAE                  | 0.0384       | 0.0413   |

- All linear regression assumptions were successfully validated:
  - ✅ Linearity  
  - ✅ Normality  
  - ✅ Homoscedasticity  
  - ✅ No Multicollinearity  

---

## 💡 Key Insights

- Visitors and trailer views significantly boost first-day content views  
- Releasing content on **Wednesdays, Saturdays, Sundays** leads to higher views  
- **Major sports events negatively impact** content viewership  
- **Summer season** shows the largest seasonal boost to views  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Linear Regression (OLS)  

---

## ✅ Business Recommendations

- Prioritize trailer campaigns before release  
- Plan content launches on high-viewership days  
- Avoid major sports event dates for new content releases  
- Leverage seasonal trends, especially **Summer**, for major content launches  
- Invest in visitor acquisition strategies to boost platform traffic 


