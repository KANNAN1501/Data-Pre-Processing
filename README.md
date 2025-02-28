# Data-Pre-Processing
Data Pre-Processing of Diabetes Dataset
The objective is to perform a thorough pre-processing of the diabetes dataset. The goal is to
understand the dataset's structure, clean and prepare the data for further analysis, and address
any issues related to outliers and missing values.
Dataset Link:
https://raw.githubusercontent.com/ArchanaInsights/Datasets/main/diabetes.csv

🔧 Preprocessing Steps
1️⃣ Data Cleaning
✔ Rename columns for clarity (e.g., No_Pation → Patients).
✔ Check and correct unique values in categorical columns (Gender, CLASS).
✔ Generate statistical summaries of numerical data.
✔ Visualize numerical columns using box plots.
✔ Identify & handle missing values (mean/median/mode imputation).
✔ Handle outliers appropriately:

Retain: AGE, HbA1c, BMI.
Filter: Cr (>99.5th percentile), Urea (>99.9th percentile).
Remove: Extreme outliers in lipid-related columns (LDL, HDL, etc.).
✔ Remove duplicate rows.
2️⃣ Data Transformation
✔ Feature Engineering: Encode categorical variables (e.g., Gender).
✔ Feature Scaling: Standardize or normalize numerical columns (AGE, BMI, Cr) for consistency.
