# Data Science Portfolio

A collection of data science projects demonstrating data cleaning, exploratory analysis, predictive modelling, visualisation and interpretation.

## Projects

### 1. Predicting Dengue Cases Using Climate and Environmental Data

**Project summary:**  
This project investigated whether climate and environmental variables can improve short-term dengue case forecasting in Maynas, Loreto, Peru. Public dengue surveillance data was combined with climate and environmental datasets, including rainfall, humidity, temperature, wind, pressure and vegetation indicators. The final modelling task was framed as a one-week-ahead regression problem.

**Methods used:**  
Python, pandas, matplotlib, seaborn, scikit-learn, XGBoost, statsmodels, SARIMA/SARIMAX, feature engineering, chronological train-validation-test splitting.

**Key findings:**  
The best final model was a climate-enhanced XGBoost model, achieving a final test MAE of 11.13 and RMSE of 21.22. Recent dengue incidence was the strongest predictor, while climate variables provided a modest improvement over the history-only model.

**What this project demonstrates:**  
- Public health data science
- Time-series feature engineering
- Machine-learning model comparison
- Careful prevention of data leakage
- Clear communication of model performance
