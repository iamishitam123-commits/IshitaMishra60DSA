# IshitaMishra60DSA
ML project for house price prediction

## Project Overview
This project focuses on predicting house sale prices using machine learning models based on various housing-related features. The dataset includes both numerical and categorical features describing residential properties.

## Objective
The objective of this project is to build a machine learning model that accurately predicts house prices and identifies the key factors influencing property value.

## Dataset
The project uses the Ames Housing Dataset, which contains detailed information about residential homes.

### Sample Features
- MSSubClass
- MSZoning
- LotArea
- Street
- LotShape
- OverallQual
- SaleType
- SaleCondition

### Target Variable
- SalePrice

## Data Preprocessing
The following preprocessing steps were performed:
- Missing value handling
- Categorical data encoding
- Data cleaning
- Feature importance analysis
- Train-test splitting

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / VS Code

## Machine Learning Models Used
### 1. Linear Regression
Used as a baseline regression model for house price prediction.

### 2. Random Forest Regressor
Used to improve prediction performance and analyze feature importance.

## Model Performance

### Linear Regression
- RMSE: 0.1476
- R² Score: 0.8833

### Random Forest Regressor
- R² Score: 0.8796

## Important Features
Top important features influencing house prices include:
- OverallQual
- LotArea
- House-related structural features

## Project Workflow
1. Data Collection  
2. Data Cleaning  
3. Missing Value Handling  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  

## Project Files
- train.ipynb → Main notebook file
- README.md → Project documentation

## Conclusion
The project successfully predicts house sale prices using machine learning models. Linear Regression achieved the best performance with an R² score of 0.8833, indicating strong predictive capability.

## Author
Ishita Mishra
