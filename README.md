# breast-cancer-survival-analysis
Kaggle notebook exploring breast cancer data with visualizations, survival analysis, and statistical tests to uncover insights and patterns.

## About Breast Cancer Kaggle Dataset

This dataset of breast cancer patients was obtained from the 2017 November update of the SEER Program of the NCI, which provides information on population-based cancer statistics. The dataset involved female patients with infiltrating duct and lobular carcinoma breast cancer (SEER primary cites recode NOS histology codes 8522/3) diagnosed in 2006-2010. Patients with unknown tumour size, examined regional LNs, positive regional LNs, and patients whose survival months were less than 1 month were excluded; thus, 4024 patients were ultimately included.

## Purpose

This repository contains a Kaggle notebook focused on analyzing breast cancer survival data. The analysis includes exploratory data analysis (EDA), survival analysis, and various visualizations to uncover insights into factors affecting breast cancer outcomes. The notebook aims to provide a comprehensive understanding of how different variables impact survival rates and to identify patterns within the dataset.

## Features

- **Age Distribution and Survival Analysis**: Explore age-related survival rates using Kaplan-Meier curves.
- **Stage vs. Survival Analysis**: Analyze how different cancer stages (T, N, 6th, and A stages) affect survival outcomes.
- **Tumor Size vs. Survival**: Examine the relationship between tumor size and survival months with scatter plots and regression analysis.
- **Regional Node Examination**: Study the impact of the number of regional nodes examined and positive nodes on survival.
- **Marital Status and Survival**: Investigate if marital status has an impact on survival months.
- **Survival Analysis by Race**: Investigate if Race has an impact on survival months.

## Dependencies

This notebook requires the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `lifelines`
- `scikit-learn`

You can install these dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn lifelines scikit-learn


