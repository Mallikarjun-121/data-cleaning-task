# Netflix Titles – Data Cleaning & Preprocessing

This project involves cleaning and preparing the *Netflix Titles* dataset using *Python (Pandas)* in *Google Colab*. The goal is to ensure the data is consistent, accurate, and ready for analysis or modeling.


## Tools & Technologies
- *Python (Pandas)*
- *Google Colab*


## Task Files
- Data_Cleaning_Task1 – Colab notebook containing the code  
- netflix_titles.csv – Original raw dataset from Kaggle  
- cleaned_netflix_titles.csv – Final cleaned dataset ready for analysis  


## Data Cleaning Steps

### 1. Missing Value Handling
- Removed rows with missing values in the title column (essential identifier).
- Replaced all other missing fields with the placeholder 'unknown'.

### 2. Duplicate Removal
- Identified and removed exact duplicate records to prevent redundancy.

### 3. Text Standardization
- Converted all string columns to lowercase for consistency.
- Stripped unnecessary spaces from all text fields.

### 4. Date Formatting
- Parsed and reformatted the date_added column to a consistent dd-mm-yyyy string format.

### 5. Column Renaming
- Renamed all columns to lowercase and replaced spaces with underscores  
  (e.g., Release Year → release_year).

### 6. Data Type Correction
- Converted release_year from object type to a clean, nullable integer type (Int64).

### 7. Final Output
- Cleaned dataset saved as: cleaned_netflix_titles.csv
