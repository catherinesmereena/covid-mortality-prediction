# covid-mortality-prediction
Analyzed and predicted U.S. COVID-19 mortality rates (2020–2023) using demographic trends, geospatial insights, and a Random Forest regression model (R² = 0.8473).

COVID-19 Mortality Prediction in the U.S. (2020–2023)

This project analyzes and predicts COVID-19 mortality trends across the United States using CDC data. It explores the influence of demographic, temporal, and respiratory comorbidity factors on death rates and applies machine learning to forecast mortality risk.

## Project Goals
- Identify demographic patterns in COVID-19 deaths by age and gender
- Compare COVID-19 to other respiratory causes (pneumonia, influenza)
- Evaluate changes in mortality rates over time and geography
- Build a predictive model to estimate COVID-19 mortality rate

##  Methods & Models
- Performed extensive data cleaning, encoding, and feature engineering
- Used statistical analysis (Chi-Square, summary stats) to assess risk patterns
- Trained a **Random Forest Regressor** with hyperparameter tuning
- Achieved **R² = 0.8473**, RMSE = 0.3870, and MAE = 0.1608 on the test set

##  Key Insights
- Males experienced consistently higher COVID-19 death rates than females
- Age was the strongest predictor; mortality increased significantly after age 65
- 2021 saw the highest death rates, followed by a major decline post-vaccination
- Pneumonia and influenza deaths correlated strongly with COVID-19 severity

##  Files Included
- `COVID_Mortality_Analysis.ipynb`: Full analysis & predictive modeling notebook
- `COVID_Mortality_Final_Report.docx`: Final report with figures and interpretations
- `Provisional_COVID_Deaths_by_Sex_and_Age.csv`: CDC dataset used for modeling

##  Tools Used
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Random Forest, Chi-Square test, Feature Engineering, Data Scaling


---

###  Summary
This project demonstrates how demographic and comorbidity data can be used to model COVID-19 mortality. The Random Forest model provides actionable insights for public health planning and supports future work in pandemic forecasting.
