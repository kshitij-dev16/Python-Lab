# 📊 STUDY OF PANDAS LIBRARY (Python)

Name- Kshitij Dalvi

Branch- EnTC A3

PRN- 25070123066


## 🎯 Aim of the Study

The aim of this project is to study the Pandas library and its applications in data handling.

This project focuses on:

Structured data

Exploratory Data Analysis (EDA)

Data Cleaning

## 📝 Algorithm

Import the pandas library as pd.

Create a Series using pd.Series() with a list of values.

Create a DataFrame using a dictionary of lists containing "Name" and "Marks".

Display the first and last five rows using head() and tail().

Identify structure by checking the shape, ndim, and size of the DataFrame.

Inspect metadata by displaying column names and column data types (dtypes).

Access data by selecting individual columns or specific rows using loc.

Modify the DataFrame by adding a new "Grade" column and updating specific marks.

Remove data by deleting a column using the drop() function.

Analyze statistically by calculating the mean(), mode(), min(), and max() of a column.

Filter data by applying conditions (e.g., Marks > 80).

Handle missing values by detecting them with isna(), counting them with sum(), and removing them with dropna().

## 📌 Introduction

Pandas stands for "Panel Data". It is a powerful Python library used for:

Managing structured data

Performing Exploratory Data Analysis (EDA)

Data Cleaning tasks

### 1️⃣ Pandas Data Structures

Series: A 1D labeled array. Example used: pd.Series([10,20,30,40]).

DataFrame: A 2D labeled data structure. Example used: A table with "Name" and "Marks" columns.

### 2️⃣ Data Inspection

df.shape: Returns the structure (e.g., 3 rows and 2 columns results in (3, 2)).

df.ndim: Returns the number of dimensions (e.g., 2).

df.size: Returns the total number of elements (e.g., 6).

df.dtypes: Displays the data type of each column (e.g., object for names, int64 for marks).

### 3️⃣ Data Manipulation

Accessing Columns: Selecting specific data like df["Name"] or df["Marks"].

Accessing Rows: Using df.loc[1] to retrieve a specific record.

Updating Data: Using df.loc[0, "Marks"] = 98 to change a specific value.

Adding Columns: Creating new data fields such as "Grade" based on student performance.

Deleting Columns: Using df.drop("Grade", axis=1) to remove a column from the DataFrame.

### 4️⃣ Statistical Analysis

mean(): Finds the average value of a column (e.g., average marks).

mode(): Identifies the most frequent value (Note: multiple values can be returned for integers).

min() / max(): Finds the minimum and maximum values in a dataset.

### 5️⃣ Data Cleaning (Handling Missing Values)

Datasets often contain np.nan (Not a Number) values.

isna(): A boolean function to check for missing values (True if missing).

notna(): A boolean function to check for valid entries (True if not missing).

isna().sum(): Checks column-wise to count how many missing values exist in each column.

dropna(): Removes rows that contain NaN values to clean the dataset.

### 📂 Applications of Pandas

Filtering: Displaying specific subsets of data, such as students scoring more than 80.

EDA: Using head() and tail() to quickly browse the first and last five data entries.

Data Management: Organizing data into rows and columns for structured analysis.

### 🎯 Conclusion

Through this study of the Pandas library, the following was achieved:

Learned to create and manipulate 1D Series and 2D DataFrames.

Performed data cleaning by identifying and dropping NaN values.

Conducted basic statistical analysis and data filtering.

Updated and restructured data using indexing, labels, and column operations.
