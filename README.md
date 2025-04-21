# Sales Data Cleaning Project

This repository contains a beginner-friendly Jupyter Notebook for cleaning a sample sales dataset. The goal is to prepare the data for analysis by handling missing values, removing duplicates, standardizing text, fixing data types, and exporting the cleaned data.

## Files Included

- `sales_data_sample.csv` - The raw dataset (you'll need to add this file manually).
- `data_cleaning_beginner.ipynb` - Jupyter notebook with step-by-step data cleaning in Python.
- `sales_data_cleaned.xlsx` - The cleaned and exported version of the dataset in Excel format.

## Steps Performed in the Notebook

1. **Import Data**  
   The dataset is loaded using pandas.

2. **Identify and Handle Missing Values**  
   Rows with missing values are dropped using `.dropna()`.

3. **Remove Duplicate Rows**  
   Duplicate rows are removed using `.drop_duplicates()`.

4. **Standardize Text Values**  
   All string values are converted to lowercase and stripped of extra spaces.

5. **Rename Column Headers**  
   Column names are made consistent: lowercase and underscores instead of spaces.

6. **Check and Fix Data Types**  
   - Date columns are converted to datetime format.
   - Numeric-like columns are converted to proper numeric types.

7. **Export Cleaned Data**  
   The cleaned data is saved as an Excel file.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sales-data-cleaning.git
   cd sales-data-cleaning
   ```

2. Install the required library:
   ```bash
   pip install pandas openpyxl
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook data_cleaning_beginner.ipynb
   ```

## License

This project is open-source and available under the [MIT License](LICENSE).
