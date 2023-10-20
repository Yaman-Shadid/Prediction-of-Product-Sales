# Prediction of Product Sales

Author:
Yaman Shadid

## Introduction

The objective is to identify the optimal predictors that will enhance item sales within the context of a grocery store organization.

## Data

The dataset used in this project contains information about various products, such as item attributes, historical sales data, promotional activities, and other relevant features.

## Methods

1. **Data Collection and Source Selection:** The data was collected from [Big Mart Sales Prediction], which was chosen based on its relevance and reliability for the project's objectives.

2. **Data Cleaning:** The collected data underwent thorough cleaning to handle missing values, outliers, and inconsistencies to ensure the data's quality and integrity.

## Data Dictionary

![download](https://github.com/Yaman-Shadid/Prediction-of-Product-Sales/assets/116229037/3c0ffbb0-2ab4-41f6-933e-8a3fb3c82e53)


## Key Visuals

There exists a strong correlation between the highest item price of the product and its corresponding item sales.

![download](https://github.com/Yaman-Shadid/Prediction-of-Product-Sales/assets/116229037/a7d524b7-89cf-4d25-817f-98fa0631eba9)

Item Sales based on Fat

![download](https://github.com/Yaman-Shadid/Prediction-of-Product-Sales/assets/116229037/5b1cb354-5886-4ebd-8d9b-b31ebff009b0)

Items labeled as "Regular Fat" have been observed to exhibit higher sales compared to those labeled as "Low Fat."

## Model



Utilizing a **Random Forest Model**, we conducted item sales predictions, achieving a testing data R-Squared value of 0.46 and an RMSE of 1093.

These metrics indicate that our model can approximate item sales with a variance of 0.46 from the target price.

## Reccomendations

Additional improvements are required to get a heightened level of optimization, leading to a more favorable model capable of accurately forecasting sales. This ongoing refinement process aims to enhance the model's predictive capabilities, ensuring its effectiveness in foreseeing sales trends and patterns.

## Interpretation for revisited model

**Linear regression:**
![Linear Regression Coefficients](./Prediction-of-Product-Sales/lr_coefficients.png)
- For a product being in "Supermarket Type2", the sales would increase by 3.32e+16 units compared to a product not being in this supermarket type, keeping all other factors constant.
- For a product being sold in "OUT035", the sales would increase by 2.25e+16 units compared to a product not being sold in this outlet, keeping all other factors constant.
- For a product being sold in "OUT017", the sales would increase by 2.14e+16 units compared to a product not being sold in this outlet, keeping all other factors constant.


**Random Forest Feature**

# Random Forest Feature Importances
![Random Forest Feature Importances](./Prediction-of-Product-Sales/rf_importances.png)

**Top 5 features are:**
- Item_MRP
- Item_Visibility
- Item_Weight
- Outlet_Type_Supermarket Type1
- Outlet_Size_Unknown


## For further information
For any additional questions, please contact **Ymmnshadid@gmail.com**
