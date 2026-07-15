
# US Electricity Market Analysis
Data analysis of US electricity prices and revenues using Python and Pandas.

## Project Overview

This project analyzes historical electricity prices, sales, and revenue across the United States using Python. The objective is to identify long-term trends, compare electricity demand across sectors, and investigate seasonal consumption patterns.

---

## Dataset

- **Source:** Kaggle
- **Topic:** US Electricity Prices, Sales, Revenue and Customers
- **Coverage:** 2001–2024

> **Note:** The 2024 observations were excluded from the trend analysis because the year appears to contain incomplete data.

---

## Project Objectives

- Explore long-term electricity revenue trends.
- Compare electricity demand across major sectors.
- Analyze seasonal electricity demand patterns.
- Identify the states generating the highest electricity revenue.
- Practice the complete Google Data Analytics workflow using a real-world dataset.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Analysis Workflow

The analysis was developed incrementally through exploratory data analysis (EDA). Rather than testing a predefined hypothesis, the objective was to understand the dataset, identify potential issues, and gradually refine the analysis.

The notebook follows the workflow below:

### 1. Dataset Exploration

- Load the dataset using Pandas.
- Inspect the available variables.
- Determine the temporal coverage of the data.
- Explore the unique values of categorical variables, including states and sectors.

### 2. Data Validation

Before performing any calculations, the dataset was validated by:

- Identifying missing values.
- Checking for duplicate records.
- Inspecting the categorical variables.
- Verifying that state and sector fields contained the expected information.
- Excluding incomplete observations from 2024.

### 3. Revenue Analysis

The first stage of the analysis focuses on electricity revenue.

This includes:

- Total revenue by year.
- Linear trend analysis.
- Revenue distribution across states.
- Identification of the highest and lowest revenue-generating states.

### 4. Demand Analysis

Electricity sales are used as a proxy for demand.

The analysis investigates:

- Seasonal demand patterns.
- Average monthly demand by sector.
- Annual demand trends.
- Differences between the Residential, Commercial, and Industrial sectors.

### 5. Interpretation

Each visualization is accompanied by a discussion of the observed patterns rather than simply presenting the figures.

The notebook concludes by summarizing the main findings and discussing possible explanations and limitations of the analysis.

### 6. Future Extensions

Possible extensions of this project include:

- Interactive Power BI dashboard.
- Electricity demand forecasting.
- Machine learning models for revenue prediction.
- Regional clustering of electricity markets.

---

## Key Findings

- Electricity revenue increased steadily between 2001 and 2023.
- Residential and Commercial electricity demand exhibit clear seasonal patterns.
- Demand peaks occur around January and August, with stronger peaks during August.
- Industrial electricity demand remains comparatively stable throughout the year.
- California and Texas consistently generate the highest electricity revenues.
- The 2024 records appear incomplete and were excluded from the trend analysis.

---

## Repository Structure

```
US-Electricity-Analysis/
│
├── README.md
├── notebooks/
│   └── us_electricity_analysis.ipynb
├── data/
│   └── clean_data_electricity_us.csv
└── images/
```

---

## Future Work

Possible extensions of this project include:

- Building an interactive Power BI dashboard
- Forecasting future electricity demand
- Applying machine learning models to predict electricity revenue
- Investigating regional differences in electricity pricing

---

## Author

Created as a portfolio project.
