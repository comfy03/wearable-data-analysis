# Sleep, Physical Activity, and Depressive Symptoms

## Overview
This project explores whether wearable data on sleep duration and physical activity are associated with depressive symptom severity measured by the Beck Depression Inventory-II (BDI-II).

Using data from the GLOBEM multi-year wearable dataset, I examine whether commonly cited behavioral signals meaningfully distinguish depression severity in a real-world setting.

## Research Questions
- Is sleep duration associated with depressive symptom severity?
- Is physical activity (step count) associated with depressive symptoms?

## Dataset
- Source: [GLOBEM Dataset](https://physionet.org/content/globem/1.1/) (wearable + survey data)

## Methods
- Data cleaning and feature selection:
  - Removed intraday, normalized, and discretized features
  - Dropped variables with >95% missingness
  - Merged wearable and survey data by participant ID and date
- Exploratory data analysis and visualization


## Key Findings
- Sleep duration showed a small but statistically significant negative association with BDI-II scores.
- Physical activity (step count) did not show a significant association.

## Limitations
- Missingness and wearable compliance variability
- Lack of adjustment for potential confounders (e.g., medication, age)

## Tools
Python, pandas, matplotlib, seaborn, statsmodels

