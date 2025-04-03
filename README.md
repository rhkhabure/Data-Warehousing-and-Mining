# Data-Warehousing-and-Mining

## Problem statement
How can the bank segment its customers based on their demographics, financial behaviour, and marketing interactions to improve targeted marketing strategies?

## Objective
Utilized advanced clustering techniques, such as K-means and Hierarchical clustering, to identify distinct customer segments within the banking industry.

## Variable and data selection
The variables selected for analysis were specifically those that were present in both datasets and were deemed to hold significant relevance based on prior research

1. Age (numeric)
2. Job: type of job (categorical: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "Services") 
3. Marital: marital status (categorical: "married", "divorced", "single"; note: "divorced" means divorced or widowed)
4. Education (categorical: "unknown", "secondary", "primary", "tertiary")
5. Default: Is credit in default? (binary: "yes", "no")
6. Balance: average yearly balance, in euros (numeric) 
7. Housing: has a housing loan? (binary: "yes", "no")
8. Loan: has a personal loan? (binary: "yes", "no")
 related to the last contact of the current campaign:
9. Contact: contact communication type (categorical: "unknown", "telephone", "cellular") 
10. Month: last contact month of the year (categorical: "Jan", "Feb", "Mar", ..., "Nov", "Dec")
11. Duration: last contact duration, in seconds (numeric)
Other attributes:
12. Campaign: number of contacts performed during this campaign and for this client (numeric, includes the last contact)
13. Pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means the client was not previously contacted)
14. Previous: number of contacts performed before this campaign and for this client (numeric)
Poutcome: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")

### Data source
The data sets were sourced from Kaggle, a well-known provider of diverse datasets. The two selected data sets were carefully chosen for their similarities in structure, consistent formatting methods, and comparable size, each containing a significant number of records.

# Data Processing and Exploration
##  Data cleaning
Data cleaning was done on VS code data wrangler as its user user-friendly and provides all necessary data cleaning functions.
Below are the data-cleaning techniques used:
1. Remove duplicate rows
2. Dropping of columns that did appear in both data sets
3. Standardizing rows data types


## Data Mining Techniques
Discretization was done on the age, campaign, and Pdays columns.
For the columns, k means discretization as it automatically adapts to the dataset data and was used in previous studies yielding the best results.
The minimum support chosen was  0.5 for confidence was 0.7.

# Implementation
Import the repository and confirm that all files are present.
Run the 'EDA and others' file first. Followed by the 'Data Mining Techniques' file.
Necessary libraries were loaded, and in our case, we worked with the following: CSV, NumPy, and Pandas were used for data handling and manipulation, allowing efficient reading, processing, and structuring of large datasets. Matplotlib and Seaborn helped in data visualization, making it easier to analyze trends and patterns through graphs and plots. Apyori, MLxtend’s Apriori, and FPGrowth were utilized for association rule mining, helping to identify relationships between different variables in large datasets. PyCaret was used for automated machine learning (AutoML), simplifying model training and evaluation. KMeans from Scikit-Learn was applied for clustering, grouping similar data points to uncover patterns in customer behavior. These libraries together enabled effective data preprocessing, visualization, pattern discovery, and machine learning model development. For optimal use and to prevent version discourse, use Python 3.11.7.

## Prerequisite
USE PYTHON 3.11.7 for stability and package compatibility.
libraries to import:
1. Mlxtend
2. Sklearn
3. Pycaret
4. Apyori


## Screenshots

## Contributing
We welcome contributions! Please fork the repository, make your changes, and submit a pull request.


