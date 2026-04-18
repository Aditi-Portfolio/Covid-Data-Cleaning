# COVID-19 Data Cleaning Project

## About
Cleaned the Our World in Data COVID-19 dataset using Python and pandas.

## Dataset
Source: Our World in Data  
Rows: 350,085 | Columns: 67 (raw)

## Problems Found in Raw Data
- Several columns had 70%+ missing values
- Date column stored as plain text
- Real countries mixed with regional aggregates
- Numeric columns stored as floats

## Steps Taken
1. Audited missing values
2. Dropped columns with more than 70% missing data
3. Separated countries from regional aggregates
4. Fixed date column to datetime type
5. Fixed numeric columns to integer type
6. Filled missing case and death counts with 0
7. Standardized text columns

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Result
- Reduced from 67 columns to 38 clean usable columns
- 333,420 country-level rows ready for analysis

## Dataset
Source: Our World in Data — COVID-19 Dataset  
Downloaded from: Kaggle  
The raw dataset is not included due to file size.

## Acknowledgements

- This project was built with guidance from Claude AI (Anthropic)
- All code written and executed by me in VS Code using Jupyter Notebook
