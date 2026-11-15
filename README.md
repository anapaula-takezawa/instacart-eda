![Instacart EDA Cover](instacart-eda-cover.png)

# Instacart — Exploratory Data Analysis (EDA)

## Project Overview

This project explores customer purchasing behavior using data from the Instacart grocery delivery platform.

The goal is to identify purchasing patterns, understand customer habits, and investigate product popularity and reorder behavior through Exploratory Data Analysis (EDA).

The analysis covers order timing, customer purchasing frequency, number of items per order, product popularity, and reorder patterns.

## Objectives

- Analyze order distribution by hour and day of the week.
- Investigate the time intervals between consecutive orders.
- Examine customer purchasing frequency.
- Identify the most frequently purchased and reordered products.
- Analyze reorder rates at both product and customer levels.
- Identify the products most frequently added first to shopping carts.

## Dataset

The project uses five datasets:

| Dataset | Description |
|---|---|
| `instacart_orders.csv` | Order information and customer activity |
| `products.csv` | Product catalog |
| `order_products.csv` | Products included in each order |
| `aisles.csv` | Grocery aisle information |
| `departments.csv` | Product department information |

**Data source:** [Instacart Market Basket Analysis — Kaggle](https://www.kaggle.com/c/instacart-market-basket-analysis)

The dataset files are not included in this repository. Please obtain them from the original source before running the notebook.

## Tools and Technologies

- **Python**
- **Pandas** — Data manipulation and analysis
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Interactive analysis environment

## Project Workflow

### 1. Data Overview
- Loaded and inspected the five datasets.
- Examined data dimensions, column types, missing values, and duplicates.

### 2. Data Preparation
- Investigated and handled missing values.
- Identified and removed duplicate records where appropriate.
- Standardized data types and prepared datasets for analysis.

### 3. Exploratory Data Analysis
- Analyzed order distribution by hour and day of the week.
- Examined intervals between consecutive orders.
- Investigated customer purchasing frequency.
- Identified the 20 most frequently reordered products.
- Calculated product and customer reorder ratios.
- Analyzed the number of items per order.
- Identified the products most frequently added first to shopping carts.

## Key Findings

- Most orders are concentrated between late morning and the afternoon.
- Customers exhibit different purchasing intervals, ranging from a few days to approximately one month.
- Orders most commonly contain between 4 and 8 items.
- Bananas, organic strawberries, avocados, and other fresh products stand out among frequently reordered items.
- Reorder ratios vary considerably across customers, revealing different purchasing patterns.
- Fruits, vegetables, dairy products, and other frequently consumed items appear prominently among products added first to shopping carts.

## Conclusion

The analysis revealed distinct purchasing patterns across customers, including differences in order frequency, product selection, and reorder behavior.

The findings provide insights into product demand and recurring purchasing habits, which can support business decisions related to inventory management, product availability, and customer engagement strategies.

## Repository Structure

```text
instacart-eda/
│
├── EDA_exploratory_data_analysis.ipynb
├── README.md
└── .gitignore
```

## Author

**Ana Paula Takezawa**

Data
