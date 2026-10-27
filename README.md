# 🏠Smart Real Estate Price Analysis

**End-to-End Data Analytics Project using Python**

- A data analytics project exploring how property characteristics relate to house prices.
- The analysis starts with a raw housing dataset, addresses missing values, prepares date information, and uses visualizations to investigate pricing patterns.

## 🎯 Objectives
- Understand the structure and characteristics of housing data.
- Prepare the dataset for analysis by handling missing and unnecessary values.
- Examine the factors associated with house prices.
- Represent important patterns using different types of charts.
- Summarize the observations obtained from the analysis.

## 🧾Business Questions

This analysis explores questions relevant to buyers, sellers, and real-estate analysts:

- How are house prices distributed across the dataset?
- How does living area relate to sale price?
- How do bedroom and bathroom counts vary across price ranges?
- Are waterfront properties associated with higher prices?
- How are price, living area, bathrooms, bedrooms, and grade correlated?

## 🛠️Tools & Skills

- **Python** — analysis workflow
- **Pandas** — data loading, inspection, cleaning, and date conversion
- **NumPy** — numerical analysis foundations
- **Matplotlib** — histograms and scatter plots
- **Seaborn** — box plots and correlation heatmap
- **Exploratory Data Analysis (EDA)** — investigating distributions and relationships
- **Data quality handling** — missing-value detection and treatment

## 📂 Dataset

The project uses the King County House Sales dataset, which contains information about residential properties and their sale prices.

Some of the features explored include:

- Living area and lot size
- Bedrooms and bathrooms
- Number of floors
- Property condition and grade
- Waterfront and view details
- Sale price

The dataset contains **21,613 records and 22 original columns**, with *price* used as the main variable for analysis.

## ⚙️ What I Did

- Examined the dataset using basic data inspection methods.
- Checked for missing values and corrected selected data issues.
- Removed an unnecessary index column and converted the date field into the appropriate format.
- Studied house price distributions and compared prices across different property features.
- Created visualizations to better understand relationships between housing characteristics and prices.

## Key Findings

Based on the visual analysis in the notebook:
- Larger living areas generally correspond to higher sale prices.
- Price distributions vary across bedroom counts; adding bedrooms does not necessarily mean a proportional price increase.
- Bathroom count shows a visible relationship with price, although a chart alone does not establish causation.
- Waterfront properties appear to occupy a higher-priced segment.
- Among the selected features, living area "sqft_living" has the strongest correlation with price.

## ⚠️Limitations & Next Steps

- The analysis is exploratory; it does not train or evaluate a house-price prediction model.
- Location is explored through the available location fields, but the notebook does not provide a dedicated geographic analysis.
- The current notebook presents selected charts rather than an interactive dashboard.

## Project Takeaway
This project demonstrates a practical Python EDA workflow: inspecting a real-world dataset, handling missing values, preparing dates, visualizing relationships, and translating patterns into understandable real-estate insights.


