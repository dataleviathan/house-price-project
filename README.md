**Chicago House Price Prediction and Classification**

**Overview**

This project analyzes the 2021 Chicago housing data to build predictive and classification models for home prices across five geographic areas. The goal is to help potential buyers, sellers, and real estate professionals make informed decisions.

**Objectives**

• Predict housing prices using linear and multiple regression models.

• Classify houses as "affordable" or "expensive" using LPM, logistic regression, and random forest.

• Compare model performance across different areas in Chicago.

• Identify influential features like square footage, number of bathrooms, and building age.

**Dataset**

The dataset includes 12 variables:

ZIP, HOUSEID, HPRICE, LOG_PRICE, SQFT, LOG_SQFT, BEDROOM,
BATHROOM, GARAGE, AGEBLD, FIREPLACE, SOLD_30DAY

Houses were labeled as expensive (1) or affordable (0) using the median price of $324,000.

**Methods**

Descriptive Statistics & Visualizations: Histograms, scatter plots, ANOVA.

Clustering: K-Means to identify house groupings.

Regression: Linear and multiple regression for price prediction.

Classification: LPM, logistic regression, and random forest for price level.

Model Evaluation: R², p-values, and AUC scores.

**Key Results**

Linear regression using SQFT explains ~54% of price variance.

Multiple regression with all features increases R² to ~61.5%.

Random forest (mtry = 2, trees = 600) achieved the highest AUC (~0.887) for classification.

Model performance varied by area; results tailored per region.

**Conclusion**

• Best predictor of price: Multiple Regression using SQFT, AGEBLD, BEDROOM, BATHROOM, GARAGE, FIREPLACE.

• Best classifier of price level: Random Forest.

• Additional features (e.g., location quality, crime rate) could further improve predictions.
