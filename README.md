# Used Car Price Prediction - EDA & Feature Engineering

## Dataset Overview

This project explores a Used Car Price Prediction dataset to understand factors affecting vehicle prices. The dataset contains vehicle details such as brand, model, year, mileage, fuel type, engine details, transmission, and price.

The objective is to perform Exploratory Data Analysis, clean the dataset, and create meaningful features for future Machine Learning models.

---

## Data Quality Issues Identified

- Missing values were present in multiple columns.
- Duplicate records were identified.
- Price values contained currency symbols and commas.
- Mileage values contained text formatting such as "mi.".
- Numerical columns required proper conversion.

---

## Cleaning Techniques Applied

- Converted price from text to numeric format.
- Converted mileage from text to numeric format.
- Removed duplicate records.
- Handled missing values.
- Identified and analyzed outliers.

---

## Feature Engineering Performed

Created five new features:

1. Car_Age
2. Price_per_Mile
3. Luxury_Brand
4. High_Mileage
5. Vehicle_Age_Group

---

## Key Business Insights

1. Vehicle age has a significant impact on used car prices.

2. Cars with lower mileage generally have higher resale values.

3. Luxury brands tend to maintain better resale prices compared to regular brands.

4. Extremely high-priced vehicles appear as outliers and require careful handling before Machine Learning.

5. Engineered features provide additional information that can improve future price prediction models.

---

## Files Included

- task-3.ipynb
- cleaned_used_cars.csv
- README.md