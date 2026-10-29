# Titanic Data Preprocessing and Exploration

This project demonstrates a Python script for basic data preprocessing and exploratory data analysis (EDA) using the classic Titanic dataset.

## Features & Steps Covered
* **Dataset Inspection:** Displays data frame information (`df.info()`) and statistical summaries (`df.describe()`).
* **Missing Value Handling:** 
  * Drops the highly sparse `Cabin` column.
  * Imputes missing `Age` values using the median.
  * Imputes missing `Embarked` values using the mode.
* **Data Cleaning:** Removes duplicate rows if any are present.
* **Feature Encoding:** Maps categorical values in the `Sex` column to numerical values (`male: 0`, `female: 1`).
* **Data Visualization:** Generates a histogram detailing the **Age Distribution** of the passengers using Seaborn and Matplotlib.

## Dependencies
Ensure you have the following libraries installed:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Code Execution
The workflow utilizes `pandas`, `numpy`, `seaborn`, and `matplotlib` to clean the dataset and output a stylized distribution plot.
