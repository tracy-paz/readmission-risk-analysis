# Healthcare Readmission Risk Analysis

## Overview
This project explores factors associated with 30-day hospital readmission and demonstrates an end-to-end analytics workflow focused on data quality, exploratory analysis, and interpretable modeling to support decision-making.

## Business Question
Which patient and encounter-level factors are most associated with 30-day readmission risk, and how can these insights support reporting and operational planning?

## Data
- De-identified healthcare dataset used for academic analysis
- Includes demographic, clinical, and utilization-related variables
- No proprietary or employer data used

## Approach
1. Data cleaning and validation to ensure consistency and reliability  
2. Exploratory analysis to identify trends and potential drivers  
3. Baseline predictive modeling (logistic regression) with emphasis on interpretability  
4. Evaluation using confusion matrix and ROC-AUC  

## Key Insights
- Prior utilization and length of stay were stronger predictors than demographics alone  
- Certain clinical conditions showed elevated readmission risk  
- Results highlight opportunities for targeted follow-up and reporting improvements  

## Tools
- SQL
- Python (pandas, numpy, scikit-learn)
- Jupyter Notebook

## Notes
This project emphasizes clear documentation, cautious interpretation, and data quality practices appropriate for healthcare analytics environments.
