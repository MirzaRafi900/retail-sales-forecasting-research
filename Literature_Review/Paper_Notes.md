# Literature Review Notes

## Paper 1

Title:
Sales Forecasting Using Machine Learning Algorithm in the Retail Sector

Authors:
Saira Malik, Muhibullah Khan, Muhammad Kamran Abid, Naeem Aslam

Year:
2024

Research Objective:
To develop and compare machine learning and time-series forecasting models for predicting retail sales and identifying the most accurate forecasting approach.

Research Questions:
1. Can machine learning improve retail sales forecasting accuracy?
2. Which forecasting model performs best for retail sales prediction?
3. What factors significantly influence retail sales?

Methodology:
The study used three forecasting approaches:

- XGBoost
- FB Prophet
- ARIMA

The researchers performed:
- Data preprocessing
- Missing value treatment
- Feature engineering
- Correlation analysis
- Exploratory Data Analysis (EDA)
- Model training and evaluation

Models were evaluated using:
- R² Score
- RMSE
- MAE 

Dataset:
Rossmann Store Sales Dataset obtained from Kaggle.

Files included:
- Store.csv
- Train.csv
- Test.csv
- Sample Submission.csv

The dataset contained multiple variables such as:
Store, Sales, Customers, Promo, SchoolHoliday, CompetitionDistance, StoreType, and others. 

Results:

Model Comparison:

XGBoost:
- R² = 0.936
- RMSE = 5.2567
- MAE = 4.1429

FB Prophet:
- R² = 0.824
- RMSE = 8.9231
- MAE = 7.6714

ARIMA:
- R² = 0.368
- RMSE = 1113.4
- MAE = 970.50

The XGBoost model achieved the best performance and outperformed both FB Prophet and ARIMA. 

Limitations:
1. Only three forecasting models were compared.
2. The study primarily focused on the Rossmann dataset.
3. Deep learning approaches were not fully explored. 

Future Work:
The authors suggested:
- Using more accurate datasets.
- Exploring additional machine learning techniques.
- Investigating deep learning methods for sales forecasting. 

What I Learned:
1. Retail sales forecasting is an important business problem.
2. Data preprocessing and feature engineering play a significant role in prediction quality.
3. XGBoost can achieve better forecasting performance than classical time-series methods such as ARIMA.
4. Machine learning models can help businesses improve inventory planning, decision-making, and profitability.
5. Model evaluation should use multiple metrics such as R², RMSE, and MAE. 
