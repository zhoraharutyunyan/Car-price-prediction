
🚗 Car Price Prediction X
Project Overview
This repository contains my solution for the Car Price Prediction X competition on Kaggle, where the goal is to predict the market price of used cars based on their features and specifications.

📊 Dataset
The competition dataset is sourced from auto.am, a leading Armenian automotive platform, and includes a variety of vehicle attributes—such as make, model, year, mileage, engine specs, body type, and more—to capture realistic market conditions 


🎯 Objective
Develop and train regression models to accurately estimate the selling price of cars given their characteristics. This is a classic supervised regression problem, with real-world relevance for buyers, sellers, and pricing engines .

🔍 Key Contributions
Data Exploration & Cleaning

Imputed missing values, standardized categories (e.g. model names, fuel types).

Performed feature engineering: age calculation, mileage binning, encoding categorical variables.

Model Development

Trained multiple regression algorithms (Linear Regression, Random Forest, Gradient Boosting).

Applied hyperparameter tuning and k-fold cross-validation.

Evaluated model performance using RMSE and R² metrics.

Pipeline & Deployment

Built a streamlined data pipeline ready for new data ingestion.

Exported trained model with usage scripts for batch or interactive predictions.
