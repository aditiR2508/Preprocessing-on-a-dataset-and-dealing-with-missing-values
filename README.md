# Preprocessing-on-a-dataset-and-dealing-with-missing-values
# Experiment-12
## Title: To perform Data Preprocessing and Handling Missing Values in Python
## Aditi Rathore
## 25070123006
## EnTC A-1
# Aim
## To study data preprocessing techniques and perform handling of missing values using various Python functions and operations.

# Theory
## Data preprocessing is the process of cleaning and preparing raw data before performing data analysis or building machine learning models.
## Real-world datasets often contain:
### •	Missing values
### •	Incorrect data formats
### •	Duplicate records
### •	Inconsistent values
## Handling these issues improves data quality and accuracy of analysis.
## One of the most common preprocessing tasks is handling missing values. Missing values may appear as:
### •	NaN
### •	NULL
### •	Blank cells
### •	Symbols like ?, -, NA

# Data Preprocessing Functions / Operations
## 1. Display First Records
### Shows the first few rows of the dataset. Function ---> head()

## 2. Display Last Records
### Shows the last few rows of the dataset. Function ---> tail()

## 3. Display Dataset Information
### Shows number of rows, columns, data types, and missing values. Function ---> info()

## 4. Check Data Types
### Shows data type of provided data. Function ---> dtypes

## 5. Identify Missing Values
### Returns True for missing values. Function ---> isnull()

## 6. Count Missing Values
### Displays the total missing values in each column. Function ---> isnull().sum()

## 7. Detect Non-Missing Values
### Returns True for valid values. Function ---> notnull()

## 8. Replace Missing Symbols
### Sometimes missing values appear as special characters like ?, used to convert symbols into NaN values. Function ---> replace()

# Methods to Handle Missing Values
## 1. Remove Rows with Missing Values
### Removes rows containing missing data. Function ---> dropna()

## 2. Remove Columns with Missing Values
### Removes columns containing missing values. Function ---> dropna(axis=1)

## 3. Fill Missing Values
### Used to replace missing values with another value. Function ---> fillna()

## 4. Replace Missing Values with Mean
### Used for numerical data. Function ---> mean() or fillna()

## 5. Replace Missing Values with Median
### Useful when the dataset contains outliers. Function ---> median() or fillna()

## 6. Replace Missing Values with Mode
### Used for categorical data. Function ---> mode() or fillna()

## 7. Forward Fill Method
### Replaces missing values with the previous value. Function ---> fillna(method='ffill')

## 8. Backward Fill Method
### Replaces missing values with the next value. Function ---> fillna(method='bfill')

# Other Preprocessing Operations
## 1. Remove Duplicate Records
### Function ---> drop_duplicates()

## 2. Count Unique Values
### Function ---> nunique()

## 3. Display Unique Values
### Function ---> unique()

# Conclusion:
### Through this experiment, we have performed data preprocessing and missing value handling operations were studied using various Python functions.
