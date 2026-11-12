SWYNEX Technologies – Task 1: Data Cleaning & Preparation
Dataset Information
Dataset Name: Adult Census Income Dataset
Source: UCI Machine Learning Repository
Dataset Link: https://archive.ics.uci.edu/dataset/2/adult
Tool Used: Microsoft Excel
Project Objective
To identify and handle missing values, duplicate records, incorrect data types, and inconsistent values in a public dataset.
Data Cleaning Steps
1. Missing Values
Identified missing values represented by ?.
Replaced ? placeholders with Unknown using Excel Find and Replace.
Verified that no ? placeholders remained.
2. Duplicate Records
Used Excel Remove Duplicates.
Removed 24 duplicate records.
32,537 unique records remained.
3. Data Type Verification
Checked six numeric columns using Excel COUNT formulas.
All six columns returned 32,537 numeric values.
4. Inconsistent Values
Used Excel Find and Replace to standardize missing-value labels.
Further verification of text consistency is pending.
Output
SWYNEX_Adult_Dataset_Cleaned.xlsx
Cleaning log maintained in the Excel workbook.
Conclusion
The dataset was cleaned using Microsoft Excel. Missing-value placeholders and duplicate records were handled, and numeric columns were verified.

## SWYNEX Technologies - Task 2: Exploratory Data Analysis (EDA)

### Dataset Information
Dataset Name: Adult Census Income Dataset
Dataset Source: UCI Machine Learning Repository
Tool Used: Python (Pandas, Matplotlib)

### EDA Steps Performed

1. Loaded the cleaned dataset from Task 1.
2. Explored the dataset structure and data types.
3. Calculated descriptive statistics for numerical variables.
4. Analyzed frequency distributions of categorical variables.
5. Created histograms to visualize numerical variables.
6. Created bar charts to visualize categorical variables.
7. Identified trends, patterns, and dominant categories.
8. Added interpretations and key observations.

### Key Insights

1. Private employment is the most common workclass.
2. HS-grad is the most frequent education category.
3. Married-civ-spouse is the most common marital status.
4. Prof-specialty is the most frequent occupation.
5. Husband is the most common relationship category.
6. White is the most frequently observed race.
7. Male records are more frequent than female records.
8. United-States is the most common native country.
9. Most individuals belong to the <=50K income category.

### Output
Task2_EDA.ipynb

### Conclusion
Exploratory Data Analysis helped identify distributions, patterns, and useful insights in the Adult Census Income dataset using statistical analysis and visualizations.









































