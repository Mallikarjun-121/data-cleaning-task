# Netflix Data Cleaning Project

This project performs data cleaning and preprocessing on the Netflix Titles dataset using Python (Pandas) in Google Colab.

## Files
- `netflix_cleaning.ipynb` – Colab notebook with code
- `cleaned_netflix_titles.csv` – Cleaned dataset

## Cleaning Steps
- Handled missing values using `dropna()` and `fillna()`
- Removed duplicate rows
- Standardized text columns (lowercase, trimmed spaces)
- Converted `date_added` to datetime format
- Renamed column headers (lowercase with underscores)
- Converted `release_year` to integer type
