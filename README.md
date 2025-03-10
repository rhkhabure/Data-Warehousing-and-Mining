# Data-Warehousing-and-Mining

## Problem statement
How can the bank segment its customers based on their demographics, financial behaviour, and marketing interactions to improve targeted marketing strategies?

## Objective
Use clustering techniques (e.g., K-means, Hierarchical clustering) to identify distinct customer segments and tailor marketing campaigns to each segment to maximize engagement and conversion rates.

## Vairable and data selection
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
other attributes:
12. Campaign: number of contacts performed during this campaign and for this client (numeric, includes the last contact)
13. Pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means the client was not previously contacted)
14. Previous: number of contacts performed before this campaign and for this client (numeric)
Poutcome: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")

### Data source
The data sets were sourced from Kaggle, a well-known provider of diverse datasets. The two selected data sets were carefully chosen for their similarities in structure, maintaining consistent formatting methods and being comparable in size, each containing a significant number of records.

## Data processing and Exploration
## Data Mining techniques

# Implementation
## Prerequisite

