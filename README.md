# House_Rent_Prediction_Linear_Regression
![](https://storage.googleapis.com/kaggle-datasets-images/2355600/3968998/d30718bb6aa4dcc45d8a49805aaa7b82/dataset-cover.jpg?t=2022-07-21-10-58-17)
## 📊 About the Dataset

The dataset used in this notebook provides information about **4700+ rental properties in India**, including houses, apartments, and flats.  
It contains the following key features:

- **BHK:** Number of Bedrooms, Hall, Kitchen  
- **Rent:** Monthly rent price (target variable)  
- **Size:** Size of the property in square feet  
- **Floor:** Current floor and total number of floors (e.g., "3 out of 5")  
- **Area Type:** Whether size is measured in Super Area, Carpet Area, or Build Area  
- **Area Locality:** Name of the locality  
- **City:** The city where the property is located  
- **Furnishing Status:** Furnished, Semi-Furnished, or Unfurnished  
- **Tenant Preferred:** Owner’s preference (Bachelors, Family, or Both)  
- **Bathroom:** Number of bathrooms  
- **Point of Contact:** Contact type (owner, agent, builder)

This dataset captures the diversity of India's rental housing market, ranging from metropolitan apartments to suburban houses, reflecting varying price ranges and living conditions.

## 🎯 Problem Statement

The objective of this notebook is to **build a predictive model** using **Linear Regression** to estimate the monthly rent (`Rent`) of a property based on its features such as BHK, Size, Bathroom count, City, Furnishing Status, and other relevant attributes.  

The workflow includes:

1. **Exploratory Data Analysis (EDA)** – Understanding data distributions, correlations, and visualizing key relationships.  
2. **Feature Engineering** – Applying log transformation to normalize `Rent`, generating dummy variables for categorical features.  
3. **Modeling** – Building both single-variable and multi-variable Linear Regression models.  
4. **Evaluation** – Using metrics such as **R²**, **MAE**, and **RMSE** to evaluate model performance.  

This project aims to demonstrate how machine learning can be used to **predict rental prices** and help tenants, landlords, and property management platforms make data-driven decisions.
