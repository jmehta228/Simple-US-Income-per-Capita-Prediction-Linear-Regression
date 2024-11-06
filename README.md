# U.S. Income Per Capita Prediction with Linear Regression

This project aims to predict U.S. income per capita (IPC) using a simple linear regression model. The dataset, `USA-IPC.csv`, includes income data across several years, and the project follows a straightforward approach to visualize and model the relationship between year and income.

## Steps in the Project:

1. **Data Exploration**:  
   The dataset is loaded and examined, checking the structure, basic information, and sample rows to understand the data's layout.

2. **Visualization**:  
   A regression plot is created using Seaborn to visually assess the linear relationship between year and income. The correlation coefficient is calculated as 0.993, which indicates a very strong positive linear relationship.

3. **Model Training**:  
   A simple linear regression model from Scikit-Learn is trained using the year as the independent variable and income as the dependent variable.

4. **Prediction**:  
   The model is used to predict income for the year 2023.

## Summary

The project provides a baseline linear model for income prediction, showing that income per capita has increased consistently over the years, making it predictable with a high degree of accuracy using linear regression.
