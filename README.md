📄 Overview
This project involves building a predictive model to identify the key factors that drive first-day content viewership for an OTT (Over-The-Top) platform called ShowTime. The project was part of my Post Graduate Program in Data Science (PGPDS.O. MAR25.A).

The objective was to assist ShowTime in improving their content performance through data-driven insights.

🎯 Problem Statement
With the increasing shift from traditional television to OTT platforms, understanding the factors that influence first-day content viewership is critical. The goal is to:

✔ Identify the driving factors for first-day viewership
✔ Build a reliable regression model to predict viewership
✔ Provide actionable business recommendations

🗃 Dataset
The dataset includes:

Visitors: Average number of visitors (in millions)

Ad Impressions: Number of ad impressions (in millions)

Major Sports Event: Presence of major sports events on release day

Genre: Genre of the content

Day of the Week: Day of content release

Season: Season of release

Trailer Views: Number of trailer views (in millions)

Content Views: First-day content views (target variable, in millions)

🔧 Key Steps
Exploratory Data Analysis (EDA)

Univariate & Bivariate Analysis

Correlation Analysis

Data Preprocessing & Encoding

Model Building: Linear Regression

Model Evaluation & Assumptions Testing

Business Insights & Recommendations

📊 Model Performance
R² (Training): 78.9%

R² (Test): 76.2%

RMSE (Test): 0.0511

MAE (Test): 0.0413

Model assumptions like linearity, normality, homoscedasticity, and absence of multicollinearity were successfully validated.

💡 Key Insights
Visitors and trailer views significantly boost first-day content views

Releasing content on Wednesdays, Saturdays, Sundays leads to higher views

Major sports events negatively impact content viewership

Summer season shows the largest seasonal boost to views

🛠 Tools & Technologies
Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)

Jupyter Notebook

Linear Regression (OLS)

✅ Business Recommendations
Boost trailer campaigns before release

Plan content launches on high-viewership days

Avoid major sports event dates

Leverage seasonal trends for major content launches

Invest in acquiring platform visitors
