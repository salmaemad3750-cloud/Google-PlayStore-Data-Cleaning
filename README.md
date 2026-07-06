# Google Play Store Data Cleaning

## Project Overview

This project focuses on cleaning the Google Play Store dataset using Python and Pandas. The objective is to prepare the dataset for future data analysis by handling missing values, removing duplicates, correcting data types, and exporting a clean dataset.

## Dataset

- Dataset: Google Play Store Apps
- Original Rows: 10,841
- Final Rows: 10,357

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook (VS Code)

## Data Cleaning Steps

- Loaded the dataset
- Inspected dataset information
- Checked missing values
- Filled missing values
  - Rating → Median
  - Type → Mode
  - Content Rating → Mode
  - Current Ver → Mode
  - Android Ver → Mode
- Removed duplicate records
- Cleaned Reviews column
- Cleaned Size column
- Cleaned Installs column
- Cleaned Price column
- Removed corrupted record (Index 10472)
- Converted Last Updated to datetime
- Verified data types
- Exported cleaned dataset

## Files

- `data_cleaning.ipynb`
- `googleplaystore.csv`
- `googleplaystore_cleaned.csv`
- `Project_Documentation.docx`

## Outcome

The final dataset is clean, consistent, and ready for exploratory data analysis and machine learning tasks.
