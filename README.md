# Diwali Sales Analysis

Exploratory Data Analysis (EDA) project on Diwali sales data using Python to identify customer behavior and high-performing segments.

## Project Overview

This project analyzes Diwali sales transactions to understand:
- who buys more during the Diwali season,
- which regions and occupations contribute the most sales,
- and which product categories perform best.

The analysis is implemented in the notebook:
- `/home/runner/work/diwali-sales-analysis/diwali-sales-analysis/Sales_Data_Analysis.ipynb`

## Dataset

Source file:
- `/home/runner/work/diwali-sales-analysis/diwali-sales-analysis/sales data new.csv`

Dataset highlights:
- 11,251 records
- 15 columns (including customer, demographic, product, and purchase details)
- Columns `Status` and `unnamed1` are fully empty and removed during cleaning
- `Amount` has a small number of missing values that are dropped during preprocessing

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Workflow

1. Load and inspect raw data
2. Check and handle missing values
3. Remove irrelevant empty columns
4. Fix datatypes (e.g., `Amount` to integer)
5. Perform grouped analysis and visualizations by:
   - Gender
   - Age Group
   - State
   - Marital Status
   - Occupation
   - Product Category

## Key Insights

- Female customers show higher overall purchasing power.
- The age group **26–35** contributes strongly to purchases.
- Top contributing states include **Uttar Pradesh, Maharashtra, and Karnataka**.
- Married women represent a high-value customer segment.
- Occupations such as **IT, Healthcare, Aviation, and Banking** stand out.
- Product categories like **Clothing, Food, and Electronics** are among the top sellers.

## How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r /home/runner/work/diwali-sales-analysis/diwali-sales-analysis/requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook /home/runner/work/diwali-sales-analysis/diwali-sales-analysis/Sales_Data_Analysis.ipynb
   ```
4. Run cells in order.

## Repository Structure

- `/home/runner/work/diwali-sales-analysis/diwali-sales-analysis/Sales_Data_Analysis.ipynb` → complete EDA notebook
- `/home/runner/work/diwali-sales-analysis/diwali-sales-analysis/sales data new.csv` → raw dataset
- `/home/runner/work/diwali-sales-analysis/diwali-sales-analysis/requirements.txt` → project dependencies
- `/home/runner/work/diwali-sales-analysis/diwali-sales-analysis/README.md` → project documentation
