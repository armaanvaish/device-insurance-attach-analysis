# Device Insurance Attach % Analysis & January Prediction

## Overview
This project analyzes historical device insurance attach percentages across retail stores for Jumbo & Company.
Attach percentage indicates the proportion of device sales where customers also purchase an insurance plan.

The objective is to:
- Identify performance trends at store and branch levels
- Categorize stores based on performance
- Predict January attach percentage at the store level using historical data

---

## Dataset
- Monthly attach percentage data from **August to December**
- **163 retail stores** across multiple branches
- Attach percentage values range between 0 and 1

---

## Key Analysis Performed
- Exploratory Data Analysis (monthly, branch, and store-level)
- Store performance categorization (Low / Medium / High)
- Trend-based January attach percentage prediction using linear regression

---

## Modeling Approach
A simple linear regression model was trained per store using month-wise attach percentage trends.
This approach was chosen to maintain interpretability and avoid overfitting given limited historical data.

---

## Outputs
- Clean Jupyter Notebook with full analysis
- PDF report summarizing insights and recommendations

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## How to Run
1. Open the notebook in the `notebook/` folder
2. Install required libraries if needed
3. Run all cells top to bottom
