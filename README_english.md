# Credit Card Application Data and Credit Record Data Analysis

## Repository Outline

1. README_bahasa.md
2. README_english.md
3. notebook.ipynb
4. Dashboard.png

## Problem Background
1.  Understanding the distribution of customers applying for credit cards based on income source, marital status, age, debtor income, and credit history (if any), grouped by gender.
2. Understanding the credit quality of existing bank customers.
3. Identifying factors that are related to Non-Performing Loan (NPL) history.

The scope is limited to data analysis and statistics only, excluding predictive analysis or machine learning. The goal is that the results of this analysis can serve as a reference for adjusting product strategies and risk management to be more relevant to customer needs.

## Project Output
1. Python notebook
2. Dashboard

## Data
The dataset used is called Credit Card Approval Prediction.

Sumber : https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction?select=application_record.csv

It consists of two datasets:

1. `application_record.csv`:
    Contains 17 columns and 438,447 rows, with 10 numerical columns and 7 categorical columns. Missing values are only present in the OCCUPATION_TYPE column.
2. `credit_record.csv`:
    Contains 3 columns and 1,048,575 rows, with 2 numerical columns and 1 categorical column. No missing values.

## Method
This project is an exploratory data analysis (EDA) and statistical testing. The statistical tests used are:

1. Descriptive analysis (measures of central tendency).
2. Inferential analysis (Chi-Square test).

## Stacks
Python, Pandas, Numpy, datetime, scipy, matplotlib.pyplot, seaborn, scipy.stats
    
    import pandas as pd
    import numpy as np
    from datetime import datetime
    from pandas.tseries.offsets import DateOffset
    from scipy import stats
    import matplotlib.pyplot as plt
    import seaborn as sns
    from scipy.stats import chi2_contingency

## Reference
Dataset : https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction?select=application_record.csv


Dashboard  : https://public.tableau.com/views/CreditCard_17526778396820/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
