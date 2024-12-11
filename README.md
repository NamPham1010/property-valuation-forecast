# Property Valuation Forecast

The dataset for this project is taken from Kaggle with the following link: https://www.kaggle.com/datasets/agungpambudi/property-sales-data-real-estate-trends
The original dataset is taken from the Milkwaukee real estate property sales data from 2002-2004 merged into one property sales dataset.

**Project Overview**

This project focuses on developing a machine learning framework to predict property sale prices in the real estate market using historical data. The goal is 
to leverage real estate property-specific features to understand key factors influencing property values across categories and to provide a predictive model based
on that knowledge to assists investors, developers, homeowners, etc. on making well informded decisions when purchasing properties.

**Goal**
The goal of this project is to develop a machine learning model that can accurately predicts property prices based on historical transactional data. It will analyze key
features that influence property values and provide insights for stakeholders. The goal is for this model to achieve a R2 score > 0.6 (due to real estate being influenced by
many factors). RMSE should be <$50000 (10%-20% of the mean price) and MAE <$35000.

This means that model explain >60% of the variance, average error within 20% of mean sale price and average absolute error within 15% of mean price.

Dataset:
Source: Milwaukee historical property sales data (2002-2018) via Kaggle
Key Features:
FinishedSqft: Total finished square footage of the property.
Property_Age: Age of the property in years. *Engineered Feature
Stories: Number of stories in the building.
Rooms_Per_Unit: Average number of rooms per unit. *Engineered Feature
Total_Bathrooms: Sum of full and half bathrooms. *Engineered Feature
Lotsize: Lot size associated with the property.
Target Variable:
Sale_price: The sale price of the property.
