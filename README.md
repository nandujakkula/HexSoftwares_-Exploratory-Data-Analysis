Titanic EDA & Data Cleaning (TASK‑1)
Exploratory Data Analysis (EDA) and basic cleaning on the Titanic passenger dataset using Pandas, NumPy, Matplotlib, and Seaborn.

Repository Contents
<img width="121" height="28" alt="image" src="https://github.com/user-attachments/assets/e1778115-08b0-450a-9e9e-e04b59756aaf" /> Jupyter Notebook with all code, charts, and prints
Dataset:
•	Expects a Titanic CSV. In the notebook it’s referenced via a local Windows path:
<img width="682" height="55" alt="image" src="https://github.com/user-attachments/assets/b2c65f91-6439-4a8e-bc68-56647b1342a7" />
Requirements
•	Python ≥ 3.10 (tested with 3.12.6)
•	Jupyter Notebook
•	pandas, numpy, matplotlib, seaborn
What the Notebook Does
1.	Load dataset from CSV into a Pandas DataFrame.
2.	Inspect schema: lists object vs numeric columns and prints	.
3.	Missing values & duplicates
4.	Displays df.isna().sum()	and duplicate count.
5.	Plots a bar chart of missing values per column.
6.	Data cleaning:
7.	Drops Cabin (high missingness).
8.	Fills Age with median.
9.	Fills Embarked with mode.
10.	Encodes categoricals:
<img width="340" height="52" alt="image" src="https://github.com/user-attachments/assets/8f8cca44-c4fe-4215-8cc9-e28f6d53b2b6" />,<img width="49" height="28" alt="image" src="https://github.com/user-attachments/assets/87395287-2391-47e8-9bbf-d03313a0ec20" />



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

 
) and imputation steps provide a baseline for
 
•	Classic Titanic dataset (commonly available via Kaggle and other sources).

 



