# 📊 DATASET CREATION AND LOADING (Python)


Name- Kshitij Dalvi
Branch- EnTC A3
PRN- 25070123066


## 📌 Introduction  

In data science, the ability to both generate synthetic data and load real-world datasets is fundamental. This experiment covers the transition from manual data entry in Python to handling large-scale external CSV files, which is a key step in Exploratory Data Analysis (EDA).

## 🎯 Aim of the Study  
The aim of this project is to demonstrate the process of manually creating a structured dataset, saving it as an external file, and loading established datasets for analysis.

This project focuses on:

Creating a dictionary-based dataset.

Converting dictionaries into Pandas DataFrames.

Exporting data to .csv format.

Loading external .csv files using read_csv.

Performing high-level data summaries (head, tail, info, describe).

### 📝 Algorithm 

Import the necessary library pandas as pd.

Define a dictionary containing student data (Roll_No, Gender, Department, CGPA).

Construct a DataFrame from this dictionary using pd.DataFrame().

Export the DataFrame to a file named student.csv using to_csv().

Access specific data subsets, such as individual columns or rows filtered by Roll Number.

Modify the dataset by adding a "Grade" column and deleting the "Gender" column.

Load an external dataset (Cars93.csv) using pd.read_csv().

Inspect the loaded dataset using size, head(), tail(), and info().

Generate a statistical summary of numerical data using describe().



## 📘 THEORY

### 1️⃣ Dataset Creation and Export

Manual Creation: Data is initially structured as a dictionary where keys represent column headers and lists represent rows.

CSV Export: The to_csv("filename.csv", index=False) method converts the internal DataFrame into a permanent file on the system.

### 2️⃣ Data Access & Filtering

Specific Columns: Accessed using df["Column_Name"] (e.g., viewing all Departments).

Conditional Filtering: Rows can be isolated based on specific criteria, such as df[df["Roll_No"] == 103].

### 3️⃣ DataFrame Manipulation 

Adding Columns: New features like "Grade" can be assigned as a list.

Deleting Columns: The drop() method with axis=1 and inplace=True permanently removes features like "Gender".

Aggregation: Functions like max() are used to identify top performers (e.g., finding the topper's CGPA).

### 4️⃣ Loading and Inspecting External Data

read_csv(): Used to load the Cars93.csv dataset containing 93 rows and 10 columns.



### Functions(Description)

#### to_csv() ---->Saves a DataFrame as a CSV file.
#### read_csv() ---->Loads a CSV file into a DataFrame.
#### dtypes ---->"Displays the data type of each column (int64, object, float64)."
#### mean() / median() ---->Performs basic central tendency calculations.
#### describe() --->Summarizes the distribution of numerical data.

#### df.info(): Provides a summary of the dataset, including non-null counts and memory usage.

#### df.describe(): Generates descriptive statistics (mean, std, min, max, quartiles) for all numerical columns like Price, Horsepower, and Passengers.



### 🎯 Conclusion

Through Experiment 10, the process of dataset lifecycle management was successfully implemented. We demonstrated how to build a dataset from scratch, store it locally, and perform complex manipulations like adding/deleting columns and statistical filtering. Furthermore, loading the Cars93 dataset highlighted the efficiency of Pandas in summarizing large volumes of data through simple commands.
