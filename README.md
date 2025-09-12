# Credit Card Application Data and Credit Record Data Analysis

## Repository Outline

1. README_bahasa.md
2. README_english.md
3. notebook.ipynb

## Problem Background
1.  Mengetahui distribusi nasabah yang mengajukan CC berdasarkan sumber penghasilan, status pernikahan, usia, income debitur dan riwayat kredit (jika ada). Semuanya ini dikelompokkan berdasarkan jenis kelamin.
2.  Mengetahui gambaran kualitas kredit dari nasabah existing di Bank.
3.  Faktor apa yang memiliki hubungan dengan riwayat NPL

Lingkup dibatasi pada data analisis dan statistik saja, tidak termasuk melakukan prediction analysis/machine learning. Diharapkan hasil olah data ini dapat menjadi acuan penyesuaian strategi produk dan manajemen risiko agar lebih relevan dengan kebutuhan nasabah.

## Project Output
1. Python notebook
2. Dashboard

## Data
Data yang digunakan bernama Credit Card Approval Prediction.

Sumber : https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction?select=application_record.csv

Terdiri dari 2 dataset yaitu:

1. `application_record.csv` :
   
    Berisi 17 kolom dan 438.447 baris, dengan 10 kolom numerical dan 7 kolom categorical. Terdapat missing value hanya pada kolom `OCCUPATION_TYPE`.

2. Dataset `credit_record.csv` :
    
    Berisi 3 kolom dan 1.048.575 baris, dengan 2 kolom numerical dan 1 kolom categorical. Tidak ada missing value.

## Method
Project ini adalah exploratory data analysis dan statistic tests. Statistic tests yang digunakan adalah:
 1.  Sebuah descriptive analysis yaitu central of tendency
 2.  Sebuah inferential analysis yaitu Chi-Square.

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