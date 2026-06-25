\# House Price Prediction using Machine Learning



\## Project Overview



This project develops an end-to-end machine learning pipeline for predicting residential property prices using the Ames Housing Dataset.



The objective was to build a robust regression model capable of accurately estimating house prices while maintaining interpretability through feature importance analysis and SHAP explainability.



The project includes:



\* Exploratory Data Analysis (EDA)

\* Feature Engineering

\* Data Preprocessing Pipelines

\* Multiple Regression Models

\* Hyperparameter Tuning

\* Cross Validation

\* Feature Importance Analysis

\* SHAP Explainability



\## Dataset



\*\*Dataset:\*\* Ames Housing Dataset



\* Observations: 1460

\* Initial Features: 81

\* Target Variable: SalePrice






\## Feature Engineering



The following features were created:



\* TotalSF

\* HouseAge

\* RemodelAge

\* TotalBath

\* HasGarage






\## Preprocessing



\### Numerical Features



\* Median Imputation

\* RobustScaler



\### Categorical Features



\* Most Frequent Imputation

\* One-Hot Encoding



\### Pipeline Tools



\* Pipeline

\* ColumnTransformer






\## Models Evaluated



Model             - R² Score 

Linear Regression - 0.9129

Ridge Regression  - 0.9083 

Lasso Regression  - 0.8990

Decision Tree     - 0.8131

Random Forest     - 0.8874

Gradient Boosting - 0.8995

XGBoost           - 0.9045

Tuned XGBoost     - 0.9094






\## Cross Validation Results



Model             - Mean CV R²

Linear Regression - 0.8421

Ridge Regression  - 0.8634

Tuned XGBoost     - 0.9057



Final Model Selected:



\*\*Tuned XGBoost\*\*






\## Explainability



SHAP analysis identified the most influential features:



\* OverallQual

\* GrLivArea

\* TotalBsmtSF

\* OverallCond

\* YearRemodAdd

\* GarageCars

\* Neighborhood Features






\## Results



\* Final CV R²: 0.9057

\* RMSE: 0.1275

\* MAE: 0.0889







\## Tools and Libraries



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Scikit-Learn

\* XGBoost

\* SHAP
