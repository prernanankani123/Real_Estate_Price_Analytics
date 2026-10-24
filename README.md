# 🏠 Smart Real-Estate Price Analytics

**End-to-End Data Analytics Project using Python**

# 📌 Project Overview

- This project focuses on analyzing real-estate housing data to identify the key factors influencing house prices.
- It demonstrates an end-to-end Data Analytics workflow, including data cleaning, missing value treatment, exploratory data analysis (EDA), data visualization, and business insight generation using Python.
- The dataset contains real-world issues such as missing values and outliers, making this project highly relevant for industry-level data analyst roles.

# 🎯 Project Objectives

- Clean and preprocess raw housing data
- Handle missing values using appropriate statistical methods
- Perform Exploratory Data Analysis (EDA)
- Visualize data using Matplotlib and Seaborn
- Identify price-driving factors in the housing market
- Generate actionable business insights

# 🛠️ Skills & Tools Used (ATS Optimized)

- Python
- NumPy
- Pandas
- Data Cleaning & Preprocessing
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Business Analytics

# 📂 Dataset Information

**Dataset Name:** King County House Sales Dataset (with NaN values)
**Rows:** 21,613
**Columns:** 22
**Target Variable**: price
**_Key Features:_**
**Property size:** sqft_living, sqft_lot
**Structure:** bedrooms, bathrooms, floors
**Quality:** grade, condition
**Location:** zipcode, waterfront, view
**Renovation & construction**: yr_built, yr_renovated

# 🔍 Project Workflow
## 1️⃣ Data Loading & Understanding

- Loaded dataset using Pandas
- Checked shape, data types, and summary statistics
- Identified irrelevant and missing data

## 2️⃣ Data Cleaning & Preprocessing

- Removed unnecessary index column (Unnamed: 0)
- Converted date column to datetime format
- Validated numerical and categorical features

## 3️⃣ Missing Value Treatment

**Missing values were found in:**

1. bedrooms
2. bathrooms

**Method Used:**
- Median imputation was applied to preserve data distribution and avoid the impact of outliers.

## 4️⃣ Exploratory Data Analysis (EDA)

**EDA was performed using:**
1. Histograms
2. Scatter plots
3. Box plots
4. Correlation heatmaps
**Key Analysis Areas:**
1. Price distribution
2. Relationship between price and living area
3. Impact of bedrooms, bathrooms, and grade
4. Effect of renovation, waterfront, and view
5. Location-based price variation

## 5️⃣ Feature Engineering

- New analytical features were created to improve insights:
- house_age – Age of the house
- is_renovated – Renovation indicator
- price_per_sqft – Fair price comparison metric

## 6️⃣ Segment-Wise Analysis

**Properties were analyzed across:**
- _Budget homes_
- _Mid-range homes_
- _Luxury homes_
- This helped in understanding different pricing behaviors across market segments.

## 7️⃣ Data Visualization Dashboard

- A user-friendly analytical dashboard was built using:
a. Matplotlib
b. Seaborn
- The dashboard clearly communicates insights for non-technical stakeholders.

## 📊 Key Insights

1. Living area (sqft_living) is the strongest price driver
2. Construction grade significantly impacts house prices
3. Bathrooms influence price more than bedrooms
4. Renovated and waterfront properties form premium segments
5. Lot size alone has limited impact on pricing

## 📈 Business Recommendations

1. Focus on improving construction quality rather than increasing bedroom count
2. Renovation offers strong return on investment
3. Waterfront and high-view properties should be marketed as premium assets
4. Buyers should prioritize living area over number of rooms

## ⚠️ Limitations & Assumptions

**Limitations:**

- No inflation adjustment
- Location limited to zipcode level
- No predictive modeling included

## **Assumptions:**

- Data reflects fair market conditions
- No major economic fluctuations during the period



