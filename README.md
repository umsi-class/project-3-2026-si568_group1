# project-3-2026-si568_group1
SI568 Project 3 — Data Driven Villainous Plan

## Project Overview
This analysis's main objective is to document "villainous" versus "ethical" data practices while analyzing clinical patient data to find patterns related to heart disease. After moving from raw data import to feature engineering, the project illustrates how data can be manipulated to mislead stakeholders.

## Key Features
- **Automated Data Import:** The UCI Heart Disease dataset is directly imported using the `ucimlrepo` library
- **Data Preprocessing:** - Binarization of the target variable (`num`) for a clear categorization (0 = no disease, 1 = disease present)
    - Managing missing values and assigning categorical data types.
    - Life-stage feature engineering (Age Binning: Young, Middle-aged, Senior, Elderly).
- **Comparative Visualizations:** Side-by-side comparisons of "Misleading" vs. "Ethical" charts.
- **Statistical Auditing:** Demonstrations of cherry-picking by comparing full dataset correlations against biased sub-group slices.
