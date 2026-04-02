# ⚖️ Data Normalization and Data Type Conversion using Python



---

## 👨‍🎓 Student Details
- **Name:** Kshitij Dalvi  
- **PRN:** 25070123066  
- **Batch:** A3  

---

## 📌 Experiment Title
**Data Normalization and Data Type Conversion using Python**

---

## 🎯 Objective
To understand and implement:
- Data normalization techniques to scale numerical data  
- Data type conversion to ensure correct data formats  
- Improve data quality and consistency for analysis  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  

---

## 📂 Dataset Description
The dataset contains numerical and categorical attributes such as:
- Product / Item Name  
- Price / Value  
- Quantity / Units Sold  
- Ratings / Scores  

The data may have:
- Different value ranges  
- Inconsistent data types  
- Unscaled numerical values  

---

## ⚙️ Functions Used (Detailed)

- **pd.DataFrame()** → Creates structured dataset  
- **astype()** → Converts data types (int, float, string)  
- **to_numeric()** → Safely converts values to numeric format  
- **min() / max()** → Finds minimum and maximum values  
- **apply()** → Applies function to entire column  
- **lambda function** → Used for custom transformations  
- **describe()** → Statistical summary  
- **info()** → Dataset structure and data types  

---

## 📊 Normalization Techniques Used

### 🔹 1. Min-Max Normalization
Scales values between 0 and 1

Formula: (x - min) / (max - min) 


### 🔹 2. Z-Score Normalization (Standardization)
Transforms data based on mean and standard deviation
Formula: (x - mean) / standard deviation


## 🔄 Algorithm

1. Start  
2. Import Pandas and NumPy  
3. Load or create dataset  
4. Convert into DataFrame  
5. Check current data types using `info()`  
6. Convert incorrect data types using `astype()` or `to_numeric()`  
7. Select numerical columns  
8. Apply Min-Max normalization  
9. Apply Z-score normalization  
10. Store normalized values in new columns  
11. Display summary using `describe()`  
12. Show final dataset  
13. End



## 🔁 Flowchart


START

↓

Import Libraries

↓

Load Dataset

↓

Convert to DataFrame

↓

Check Data Types

↓

Convert Data Types

↓

Select Numerical Data

↓

Apply Min-Max Normalization

↓

Apply Z-Score Normalization

↓

Store Results

↓

Analyze 

↓

Display Output

↓

END





## 📈 Key Features of Output
- Data scaled to uniform range  
- Improved comparability between features  
- Correct data types assigned  
- Clean and analysis-ready dataset  


## ✅ Conclusion
This experiment highlights the importance of scaling and formatting data before analysis. Normalization ensures fair comparison between variables, while proper data type conversion improves accuracy and efficiency in computations.
