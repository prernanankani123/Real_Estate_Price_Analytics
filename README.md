# Smart Real Estate Price Analysis

## Project Overview

Smart Real Estate Price Analysis is a Python-based data analytics project that explores housing data to understand how property characteristics relate to house sale prices. The project involves data inspection, data cleaning, preprocessing, Exploratory Data Analysis (EDA), statistical analysis, and data visualization using Python.

The analysis focuses on house prices, living area, bedrooms, bathrooms, waterfront properties, and construction grade to identify patterns and relationships that may help buyers, sellers, and real-estate analysts better understand the housing market.

## Objectives

- Understand the structure and characteristics of housing data.
- Identify and handle missing values and unnecessary columns.
- Analyze house price distribution and variations.
- Examine relationships between property features and sale prices.
- Use visualizations to identify patterns and potential outliers.
- Summarize findings to support data-informed real-estate decisions.

## Business Questions

The analysis explores the following questions:

- How are house prices distributed across the dataset?
- How does living area relate to house sale price?
- How do bedroom and bathroom counts relate to house prices?
- Are waterfront properties associated with higher sale prices?
- How does construction grade relate to house price?
- Which selected property features have the strongest correlation with price?
- How do house prices vary across different property characteristics?

## Tools and Skills

- **Python** — data analysis and preprocessing
- **Pandas** — data inspection, manipulation, and cleaning
- **NumPy** — numerical analysis, if used in the notebook
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualizations and correlation analysis
- **Exploratory Data Analysis (EDA)** — identifying patterns and relationships
- **Data Cleaning** — missing-value inspection and unnecessary-column removal
- **Date Preprocessing** — converting the sale date into the appropriate format

## Dataset

The project uses the **King County House Sales** dataset, which contains information about residential properties and their sale prices.

- **Dataset Name:** King County House Sales
- **Source:** Kaggle
- **Records:** 21,613
- **Features:** 22
- Important attributes include `price`, `bedrooms`, `bathrooms`, `sqft_living`, `sqft_lot`, `floors`, `waterfront`, `view`, `condition`, and `grade`.

## Project Workflow

### 1. Data Collection and Initial Exploration

- Loaded the housing dataset into Python using Pandas.
- Reviewed the dataset dimensions, column names, and data types.
- Examined summary statistics to understand the numerical features.
- Identified important property attributes for further analysis.

### 2. Data Cleaning and Preprocessing

- Checked the dataset for missing values.
- Identified incomplete values in selected columns, including bedrooms and bathrooms.
- Removed the unnecessary `Unnamed: 0` index column.
- Converted the `date` column into the appropriate datetime format.
- Prepared the dataset for exploratory analysis.

### 3. Exploratory Data Analysis (EDA)

- Examined the distribution of house sale prices.
- Compared house prices with living area and other property characteristics.
- Explored price differences across bedroom and bathroom counts.
- Investigated the relationship between waterfront status and house prices.
- Examined how construction grade relates to sale price.

### 4. Statistical Analysis and Visualization

- Used descriptive statistics to summarize housing data.
- Created charts to explore price distributions and property characteristics.
- Used scatter plots to examine relationships between numerical variables.
- Applied correlation analysis to identify associations between selected features and price.
- Used visualizations to summarize important patterns in the dataset.

## Visualizations

The following visualizations illustrate selected patterns and relationships identified during the analysis.

### 1. House Price Distribution

A histogram is used to examine the distribution of house sale prices.

<img width="436" height="310" alt="image" src="https://github.com/user-attachments/assets/80816b57-f6c6-4ab8-a0fd-f36d94cdb604" />

**Observation:**
The distribution helps show how sale prices vary across properties and whether prices are concentrated within particular ranges.

### 2. Living Area vs House Price

A scatter plot is used to explore the relationship between living area (`sqft_living`) and house sale price.

<img width="416" height="301" alt="image" src="https://github.com/user-attachments/assets/7756ab8f-1631-4796-8601-86a503a3f551" />

**Observation:**
Houses with larger living areas generally tend to have higher sale prices, indicating a positive relationship between living area and price.

### 3. Waterfront vs House Price

A visualization compares house prices according to waterfront status.

<img width="379" height="305" alt="image" src="https://github.com/user-attachments/assets/5b5a288c-b6fc-49f0-998f-4f894765b09c" />

**Observation:**
Waterfront properties appear to occupy a higher-priced segment of the dataset. However, waterfront status alone does not determine a property's sale price.

## Key Findings

- Larger living areas generally correspond to higher house sale prices.
- House prices vary across different bedroom counts; additional bedrooms do not necessarily produce proportional price increases.
- Bathroom count shows a visible relationship with house price.
- Waterfront properties appear to occupy a higher-priced segment.
- Construction grade has a positive correlation with house price.
- Among the selected features, `sqft_living` has the strongest correlation with `price`.

## Business Insights

- **Property size:** Living area is an important feature to examine when comparing house prices.
- **Property configuration:** Bedroom and bathroom counts should be considered alongside other property characteristics rather than in isolation.
- **Waterfront properties:** Waterfront status may be associated with higher prices, but other property features can also influence value.
- **Construction quality:** The positive relationship between construction grade and price suggests that property grade is relevant when analyzing price differences.
- **Data-driven comparisons:** Buyers, sellers, and real-estate analysts can use these patterns as a starting point for comparing properties, while considering additional factors such as location and condition.

## Repository Contents

- `Real_Estate_Price_Analytics.ipynb` — Jupyter Notebook containing the analysis, Python code, and visualizations.
- `Real_Estate_Price_Analytics.html` — HTML version of the notebook for viewing the analysis in a browser.
- `kc_house_data.csv` — Housing dataset, if included in the repository and permitted by its license.
- `README.md` — Project documentation.

## Limitations and Future Scope

- The project focuses on exploratory data analysis rather than training a house-price prediction model.
- The observed relationships do not establish cause and effect.
- The analysis examines selected housing features and may not capture every factor influencing sale prices.
- Future improvements could include deeper location-based analysis, additional statistical tests, and an interactive dashboard using Power BI.

## Conclusion

This project demonstrates a practical Python-based data analytics workflow for exploring residential property prices. Through data cleaning, preprocessing, exploratory data analysis, statistical analysis, and visualization, the project investigates how living area, bedrooms, bathrooms, waterfront status, and construction grade relate to house sale prices. The findings highlight the importance of examining multiple property characteristics when understanding housing market patterns and making informed real-estate comparisons.
