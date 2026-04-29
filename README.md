# Problem Statement 
Obesity rates vary across different socioeconomic groups in the United States. Understanding whether income level is associated with obesity prevalence may help identify health disparities and guide public health interventions.

# Hypothesis
Lower income groups have higher obesity rates compared to higher income groups across U.S states. 

# How the Data Will be Used 
The datasets contains obesity percentages categorized by income level, state, and year. By extracting the relevant columns (income group, location and obesity value), we can compare obesity prevalence between income groups and analyze whether lower income categories consistently show high obesity rates.

# Tools Used
- Python
- PySpark
- Jupyter Notebook / Spark Notebook
- Matplotlib
- GitHub

# Dataset
CDC Obesity Dataset containing:

- Year
- State
- Obesity Percentage
- Income Groups
- Education
- Age
- Gender
- Race/Ethnicity

## Analysis Performed

- Loaded CSV dataset into Spark DataFrame
- Selected relevant columns
- Filtered rows where category = Income
- Converted obesity values to numeric format
- Calculated average obesity rate by income group
- Created visualizations using Matplotlib

## Results Summary

The results support the hypothesis.

Average obesity rates by income group:

| Income Group | Average Obesity Rate |
|-------------|----------------------|
| Less than $15,000 | 35.84% |
| $15,000 - $24,999 | 34.67% |
| $25,000 - $34,999 | 33.28% |
| $35,000 - $49,999 | 32.87% |
| $50,000 - $74,999 | 32.28% |
| $75,000 or greater | 29.02% |

<img width="827" height="467" alt="image" src="https://github.com/user-attachments/assets/814c0424-aa36-4339-bcda-fc363c094adf" />



Lower income groups consistently showed higher obesity rates than higher income groups.

## Conclusion

This project found an inverse relationship between income and obesity rates. As income increased, average obesity rates decreased.

## Author

Yangchen Lhamo
