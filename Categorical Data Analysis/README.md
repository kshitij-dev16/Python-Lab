# 📊 **Experiment 11: Categorical Data Analysis using Python**
**Name:** Kshitij Dalvi
**Branch:** EnTC A3
**PRN:** 25070123066
**Date:** (Add your submission date)

---

## 📘 Title Page

**Project Title:** Categorical Data Analysis using Python
**Objective:** To study and perform categorical data analysis using the Pandas library in Python.
**Programming Language:** Python
**Libraries Used:** Pandas

---

## 🎯 Aim of the Study

To analyze categorical datasets using Python and perform operations such as frequency count, unique values, cross-tabulation, percentage distribution, filtering, grouping, and sorting.

---

## 📌 Introduction

Categorical data represents data that can be grouped into categories or labels rather than numerical values.

### Examples:

* Product Category
* Payment Method
* Delivery Type
* Customer Type

### Importance:

* Helps understand distribution
* Identifies relationships between variables
* Useful in business analytics and decision making

---

## 📂 Dataset Description

The dataset represents customer order details.

| Column Name    | Description      |
| -------------- | ---------------- |
| Order_ID       | Unique order ID  |
| Category       | Product type     |
| Payment_Method | Payment mode     |
| Delivery_Type  | Delivery option  |
| Customer_Type  | Type of customer |

---

## 📖 Study of Dataset Operations

* Creating dataset
* Converting to DataFrame
* Displaying dataset
* Frequency count
* Unique values
* Count of unique values
* Cross tabulation
* Percentage distribution
* Filtering
* Grouping
* Sorting

---

# 📘 THEORY, ALGORITHMS & FLOWCHARTS

---

## 🔹 Part 1: Creating Dataset

### Algorithm:

1. Start
2. Import pandas
3. Create dictionary
4. Convert into DataFrame
5. Display dataset
6. Stop

### Flowchart:

Start → Import pandas → Create Dictionary → Convert to DataFrame → Display → Stop

---

## 🔹 Part 2: Display Dataset

### Algorithm:

1. Start
2. Load DataFrame
3. Use print() or display()
4. Show dataset
5. Stop

### Flowchart:

Start → Load Data → Display → Stop

---

## 🔹 Part 3: Frequency Count

### Algorithm:

1. Start
2. Select categorical column
3. Apply value_counts()
4. Display result
5. Stop

### Flowchart:

Start → Select Column → value_counts() → Display → Stop

---

## 🔹 Part 4: Unique Values

### Algorithm:

1. Start
2. Select column
3. Apply unique()
4. Display values
5. Stop

### Flowchart:

Start → Select Column → unique() → Display → Stop

---

## 🔹 Part 5: Count of Unique Values

### Algorithm:

1. Start
2. Select column
3. Apply nunique()
4. Display count
5. Stop

### Flowchart:

Start → Select Column → nunique() → Display → Stop

---

## 🔹 Part 6: Cross Tabulation

### Algorithm:

1. Start
2. Select two columns
3. Apply pd.crosstab()
4. Generate table
5. Display result
6. Stop

### Flowchart:

Start → Select Columns → Crosstab → Generate Table → Display → Stop

---

## 🔹 Part 7: Percentage Distribution

### Algorithm:

1. Start
2. Select column
3. Apply value_counts(normalize=True)
4. Multiply by 100
5. Display percentage
6. Stop

### Flowchart:

Start → Select Column → Normalize Count → Convert to % → Display → Stop

---

## 🔹 Part 8: Filtering Dataset

### Algorithm:

1. Start
2. Define condition
3. Apply condition on DataFrame
4. Store filtered data
5. Display result
6. Stop

### Flowchart:

Start → Define Condition → Apply Filter → Store Data → Display → Stop

---

## 🔹 Part 9: Grouping Dataset

### Algorithm:

1. Start
2. Select grouping columns
3. Apply groupby()
4. Apply aggregation/count
5. Display result
6. Stop

### Flowchart:

Start → Select Columns → groupby() → Aggregate → Display → Stop

---

## 🔹 Part 10: Sorting Dataset ✅

### Algorithm:

1. Start
2. Select column
3. Apply sort_values()
4. Choose ascending/descending
5. Display sorted data
6. Stop

### Flowchart:

Start → Select Column → sort_values() → Arrange Data → Display → Stop

---

## 🛠 Tools Used

* Python
* Pandas
* Jupyter Notebook
* VS Code

---

## 📊 Applications

* Market analysis
* Customer segmentation
* Business analytics
* E-commerce insights
* Survey data analysis

---

## ✅ Advantages

* Easy to understand
* Identifies patterns
* Supports decision making
* Efficient using Pandas
* Handles large datasets

---

## ❌ Disadvantages

* Cannot perform direct mathematical operations
* Requires preprocessing
* Limited without visualization

---

## 🔑 Key Concepts Covered

* DataFrame creation
* value_counts()
* unique()
* nunique()
* crosstab()
* Filtering
* Grouping
* Sorting

---

## 🎯 Conclusion

Categorical data analysis using Python enables efficient analysis of non-numerical data. Using Pandas functions, we can easily study patterns, relationships, and distributions in categorical datasets.

These techniques are widely used in data science, machine learning, and business analytics to extract meaningful insights.

---

