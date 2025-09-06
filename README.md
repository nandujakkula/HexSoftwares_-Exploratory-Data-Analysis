# HexSoftwares_-Exploratory-Data-Analysis
Titanic EDA & Data Cleaning (TASK‑1)
Exploratory Data Analysis (EDA) and basic cleaning on the Titanic passenger dataset using Pandas, NumPy, Matplotlib, and Seaborn.

Repository Contents

 
•
Dataset
 
—	Jupyter Notebook with all code, charts, and prints.
 
•	Expects a Titanic CSV. In the notebook it’s referenced via a local Windows path:


 
•	Update
•	
 
to point to your local CSV before running.	
 

Requirements
•	Python ≥ 3.10 (tested with 3.12.6)
•	Jupyter Notebook
•	pandas, numpy, matplotlib, seaborn
Quick setup

How to Run

1.	Open TASK-1.ipynb in Jupyter.
2.	Edit the file_name variable to your CSV path.
3.	Run the cells top‑to‑bottom (	).
 
What the Notebook Does

1.	Load dataset from CSV into a Pandas DataFrame.
2.	Inspect schema: lists object vs numeric columns and prints	.
3.	Missing values & duplicates:
4.	Displays	and duplicate count.
 
5.	Plots a bar chart of missing values per column.
6.	Data cleaning:
7.	Drops Cabin (high missingness).
8.	Fills Age with median.
9.	Fills Embarked with mode.
10.	Encodes categoricals:
◦
◦
11.	Prints remaining missing values post‑cleaning.
12.	Descriptive statistics: prints df.describe() .
13.	Target explanation: clarifies Survived meanings —
 
14.	Distribution summaries: value counts for Pclass .
 
15.	Survival analysis: prints overall survival rate and survival rates by Sex , Pclass , and
16.	Visualizations (Matplotlib/Seaborn):
17.	Countplot: Survived
18.	Countplot: Sex × Survived
19.	Countplot: Pclass × Survived
20.	Histograms: Age , Fare
21.	Boxplot: Age by Survived
22.	Correlation heatmap of numeric features
Notes

•	The notebook suppresses warnings with	.
•	Adjust plotting backends as needed if running outside Jupyter.
Reuse

 
•	The cleaned features ( downstream modeling.
Acknowledgments
 
,
 
) and imputation steps provide a baseline for
 
•	Classic Titanic dataset (commonly available via Kaggle and other sources).
