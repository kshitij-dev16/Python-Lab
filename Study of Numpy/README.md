
# 📊 STUDY OF NUMPY LIBRARY (Python)


Name- Kshitij Dalvi

Branch- EnTC A3

PRN- 25070123066



## 🎯 Aim of the Study

The aim of this project is to study the NumPy (Numerical Python) library and understand its application in high-performance numerical computations.

### This project focuses on:


Creating and manipulating NumPy arrays.

Performing element-wise mathematical operations.

Understanding core array attributes like dimensions, shape, and data types.

Utilizing built-in functions for array generation.

Executing statistical analysis such as mean, median, and sum.

## 📌 Introduction

NumPy is a powerful Python library used for numerical and scientific computing. It is preferred over standard Python lists because it is significantly faster and more memory-efficient.

It provides support for:

Large multi-dimensional arrays.

Mathematical functions for fast operations.

Statistical operations and linear algebra.

## 📖 Study of NumPy (Implementation Details)  

Based on the experimental data provided:

Importing: The library is imported using the standard alias import numpy as np.

Creation: Arrays are initialized using np.array() for both 1D and 2D structures.

Inspection: Attributes such as .ndim (dimensions), .shape (structure), and .dtype (data type) are used to study array properties.

Generation: Built-in functions like np.zeros(), np.ones(), and np.eye() are used for specialized matrix creation.

Sequencing: np.arange() and np.linspace() are utilized to create arrays with specific numerical ranges and spacing.

## 📘 THEORY (Experimental Observations)  

### 1️⃣ Array Attributes

Dimensions (ndim): Identifies the number of axes. In this study, 1D and 2D arrays were analyzed.

Shape (shape): A 1D array with 4 elements has a shape of (4,), while a 2D array with 2 rows and 3 columns has a shape of (2, 3).

Data Type (dtype): The elements in the tested arrays were identified as int64.

### 2️⃣ Special Array Creation Functions

np.zeros((3,2)): Creates a 3x2 array filled with 0.0.

np.ones((3,3)): Creates a 3x3 symmetric matrix filled with 1.0.

np.eye(5): Creates a 5x5 identity (diagonal) matrix.

np.arange(1,10,2): Generates values from 1 to 9 with a step of 2 ([1, 3, 5, 7, 9]).

np.linspace(0,1,4): Generates 4 evenly spaced values between 0 and 1.

### 3️⃣ Mathematical Operations

NumPy supports vectorized operations that apply to every element in the array simultaneously:

Multiplication: b * 2 doubles every element in the matrix.

Addition: a + 5 adds 5 to every element in the vector.

### 4️⃣ Statistical Functions  

The library provides built-in methods for data analysis:

np.mean(): Calculates the average of array elements.

np.median(): Finds the middle value. Note: If mean and median are close, the data is likely clean and free of significant outliers.

np.max() / np.min(): Identifies the highest and lowest values.

np.sum(): Calculates the total sum of all elements.


### 🎯 Conclusion

Through this experiment, it was observed that NumPy provides a robust and efficient framework for handling numerical data compared to standard Python lists. Key takeaways include:

Successful creation and manipulation of multi-dimensional arrays.

Understanding that NumPy arrays are faster and support vectorized mathematical operations.

Ability to use built-in statistical functions to quickly analyze data sets for cleanliness and outliers.
