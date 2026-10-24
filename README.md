# 🏠Smart Real Estate Price Analysis

**End-to-End Data Analytics Project using Python**

- A data analytics project exploring how property characteristics relate to house prices.
- The analysis starts with a raw housing dataset, addresses missing values, prepares date information, and uses visualizations to investigate pricing patterns.

## Project Details

| Item | Details |
|---|---|
| Domain | Real Estate Analytics |
| Dataset | King County House Sales (with missing values) |
| Records | 21,613 |
| Original columns | 22 |
| Analysis target | `price` |
| Environment | Jupyter Notebook |

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

## 📂Dataset

The CSV contains 21,613 records and 22 columns before cleaning. The main fields include:

| Category | Example columns |
|---|---|
| Sale information | `price`, `date`, `id` |
| Property size | `sqft_living`, `sqft_lot`, `sqft_above`, `sqft_basement` |
| Structure | `bedrooms`, `bathrooms`, `floors` |
| Quality and amenities | `grade`, `condition`, `view`, `waterfront` |
| Construction | `yr_built`, `yr_renovated` |
| Location | `zipcode`, `lat`, `long` |

The dataset includes missing values in `bedrooms` and `bathrooms`, which are handled during preprocessing.

## 🔍Workflow

### 1. Load and inspect the data
- Read the CSV into a Pandas DataFrame.
- Review the dataset shape, data types, and descriptive statistics.
- Identify missing values and understand the available features.

### 2. Clean and prepare
- Remove the redundant `Unnamed: 0` index column.
- Check missing-value counts by column.
- Fill missing `bedrooms` and `bathrooms` values using their respective **mean values**.
- Convert `date` to a datetime data type.
- Recheck missing values after treatment.

### 3. Explore and visualize
The notebook uses Matplotlib and Seaborn to investigate:

- **Price distribution:** histogram to understand the spread of sale prices.
- **Living area vs. price:** scatter plot to examine their relationship.
- **Bedrooms vs. price:** box plot to compare price distributions across bedroom counts.
- **Bathrooms vs. price:** scatter plot to explore how bathroom count relates to price.
- **Waterfront vs. price:** box plot to compare waterfront and non-waterfront properties.
- **Correlation among key variables:** heatmap for `price`, `sqft_living`, `bathrooms`, `bedrooms`, and `grade`.

## Key Findings

Based on the visual analysis in the notebook:

- House prices are **right-skewed**, with relatively few high-priced properties.
- Larger living areas generally correspond to higher sale prices.
- Price distributions vary across bedroom counts; adding bedrooms does not necessarily mean a proportional price increase.
- Bathroom count shows a visible relationship with price, although a chart alone does not establish causation.
- Waterfront properties appear to occupy a higher-priced segment.
- Among the selected variables, `sqft_living` shows the strongest correlation with `price` in the notebook's correlation heatmap.

These findings describe associations in this dataset; they should not be interpreted as proof that any single feature causes a price change.

## ⚠️Limitations & Next Steps

- Mean imputation is simple, but it can be sensitive to outliers and may produce fractional values for count-like fields. Compare it with median or domain-based treatment in a future iteration.
- The analysis is exploratory; it does not train or evaluate a house-price prediction model.
- Location is explored through the available location fields, but the notebook does not provide a dedicated geographic analysis.
- The current notebook presents selected charts rather than an interactive dashboard.

## Project Takeaway

This project demonstrates a practical Python EDA workflow: inspecting a real-world dataset, handling missing values, preparing dates, visualizing relationships, and translating patterns into understandable real-estate insights.


