# Exploratory-Data-Analysis-EDA-

This repository contains the work for Task 5 of the Elevate Labs Data Analyst Internship. The objective of this task was to perform an Exploratory Data Analysis (EDA) on the Titanic dataset to extract key insights.

## Dataset
The analysis was performed on the `train.csv` dataset, which contains information about passengers on the Titanic, including their survival status.

## Analysis Process
The EDA was conducted using Python with the Pandas, Matplotlib, and Seaborn libraries in a Jupyter Notebook. The process included:
1.  **Data Loading and Initial Inspection**: Loaded the dataset and reviewed its structure, data types, and summary statistics.
2.  **Data Cleaning**: Handled missing values in the `Age` and `Embarked` columns through median and mode imputation, respectively.
3.  **Univariate Analysis**: Analyzed the distribution of individual variables like `Age` and `Fare`.
4.  **Bivariate and Multivariate Analysis**: Explored the relationships between different variables and their impact on survival using bar plots, scatterplots, and a correlation heatmap.

## Key Findings
- **Survival Rate by Gender**: Females had a significantly higher survival rate (approx. 74%) compared to males (approx. 19%), supporting the "women and children first" protocol.
- **Survival Rate by Class**: First-class passengers had the highest chance of survival (over 60%), whereas third-class passengers had the lowest (below 25%).
- **Fare Distribution**: The `Fare` was highly skewed to the right, indicating that most passengers paid a low fare. A log transformation was applied to normalize this feature for better modeling performance.
- **Family Size**: Passengers traveling with family members had a higher survival rate than those traveling alone.

## How to Run
1.  Ensure you have Python and the required libraries (pandas, seaborn, matplotlib) installed.
2.  Clone this repository.
3.  Open the `Titanic_EDA_Template.ipynb` file in Jupyter Notebook or JupyterLab.
4.  Run the cells sequentially to reproduce the analysis.
