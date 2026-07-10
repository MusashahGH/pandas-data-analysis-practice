# 📊 Pandas Complete Practice Notebook

![Pandas Logo](panda.images.png)

A comprehensive Jupyter notebook covering essential Pandas operations including DataFrame basics, merging datasets, handling null values, data aggregation, filtering, and visualization.

---

## 📁 File Overview

- **File:** `pandapractice.ipynb`
- **Topics:** Pandas DataFrame, Merging, Null Values, Aggregation, Filtering, Visualization
- **Level:** Beginner to Intermediate

---

## 📚 Topics Covered

### 1. Introduction to DataFrames
- What is a DataFrame?
- Creating DataFrames from Python lists
- Understanding rows, columns, and indexes

### 2. Creating DataFrames
- `pd.DataFrame()` - Create DataFrame with data
- Adding column names using `columns` parameter
- Adding custom row indexes using `index` parameter

### 3. DataFrame Methods - Viewing Data
- `df.head()` - View first 5 rows (or specified number)
- `df.tail()` - View last 5 rows (or specified number)

### 4. DataFrame Attributes
- `df.columns` - Get all column names
- `df.index` - Get row indexes
- `df.shape` - Get dimensions (rows, columns)
- `df.size` - Get total number of elements

### 5. DataFrame Information Methods
- `df.info()` - Get complete information about DataFrame
- `df.describe()` - Get statistical summary (count, mean, std, min, max, quartiles)
- `df.index.tolist()` - Convert index to list

### 6. Unique Values Methods
- `df.nunique()` - Count unique values in each column
- `df["column_name"].unique()` - Get unique values from a specific column

### 7. Merging and Concatenation
- `pd.merge()` - Merge two DataFrames
- Left Join concept (similar to DBMS)
- Merging on specific columns using `left_on` and `right_on`
- `how='left'` - Keep all data from left DataFrame
- Renaming columns using `rename()`

### 8. Filtering Data

#### Method 1: Basic Filtering with Conditions
```python
# Filter rows where height > 215
bios.loc[bios['height_cm'] > 215]

# Alternative way
bios[bios['height_cm'] > 215]
```



## 🚀 How to Run This Notebook

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Pandas library

### Installation

```bash
# Install pandas
pip install pandas

# Install jupyter
pip install jupyter
