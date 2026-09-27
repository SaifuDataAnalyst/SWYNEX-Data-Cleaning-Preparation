# SWYNEX - Student Performance Dataset Data Cleaning

## Dataset

Student Performance Dataset (Mathematics)

## Source

UCI Machine Learning Repository

## Dataset Size

395 rows and 33 columns

## Tools Used

- Python
- Pandas
- Jupyter Notebook

## Data Cleaning & Preparation

The dataset was inspected and prepared for analysis using Python and Pandas.

1. Dataset Structure and Data Types

- Checked the dataset structure using "df.info()".
- Checked all column data types using "df.dtypes".
- Numeric and categorical columns were found to have appropriate data types.
- No incorrect data types were identified.

2. Missing Values

- Checked all columns for missing values.
- Result: No missing values found.

3. Duplicate Records

- Checked the dataset for duplicate rows.
- Result: 0 duplicate records found.

4. Categorical Value Consistency

- Checked unique values and value frequencies for categorical columns.
- No obvious inconsistent categorical values were identified.

5. Extra Spaces

- Checked categorical values for leading or trailing spaces.
- Result: No extra spaces found.

6. Cleaned Dataset

- Created a verified copy of the dataset.
- Exported the prepared dataset as "student_mat_cleaned.csv".

## Output

The prepared dataset is saved as:

"student_mat_cleaned.csv"
