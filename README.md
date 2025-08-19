# lifeExpectencyPrediction

This project aims to predict life expectancy based on various socio-economic and health-related factors using machine learning models. The dataset includes information such as mortality rates, disease prevalence, economic indicators, and education levels for countries over multiple years.

---

## Dataset

The dataset contains records for various countries from different years and includes the following features:

- Country, Year, and Development Status  
- Health indicators (e.g., Adult Mortality, Infant Deaths, Measles, HIV/AIDS)  
- Economic and social indicators (e.g., GDP, Population, Income Composition of Resources, Schooling)  
- Immunization data (e.g., Hepatitis B, Polio, Diphtheria)  
- Expenditures and alcohol consumption  

---

## Objective

The goal is to accurately predict the Life Expectancy of a person using the above features.

---

## Models Used

| Model             | MSE  | MAE  | RMSE | R² Score |
| ----------------- | ---- | ---- | ---- | -------- |
| Linear Regression | 4.17 | 1.27 | 2.04 | 0.9517   |
| Random Forest     | 2.82 | 1.03 | 1.68 | 0.9674   |

The Random Forest Regressor achieved the best performance with an R² Score of 0.967, indicating strong predictive capability.

---

## Contents

- Data preprocessing and exploration  
- Feature engineering  
- Model training and evaluation  
- Performance comparison  
