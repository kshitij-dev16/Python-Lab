# 🦠 COVID-19 Data Analysis using Python



## 👨‍🎓 Student Details
- **Name:** Kshitij Dalvi
- **PRN:** 25070123066
- **Batch:** EnTC A3  

---

## 📌 Project Title
**COVID-19 Data Analysis Project**

---

## 📚 Course Details
- **Subject:** Data Analysis with Python  
- **Experiment:** 19 & 20 (with Advanced Extension)  
- **Date:** 15 April 2026  

---

## 📑 Table of Contents
- Abstract  
- Objectives  
- Dataset Description  
- Tools & Technologies  
- Methodology  
- Analysis & Visualizations  
- Key Insights  
- Conclusion  
- Future Scope  
- References  

---

# 📖 1. Abstract
This project presents a comprehensive analysis of COVID-19 data using Python. The dataset spans global pandemic records from January 2020 to May 2021, covering confirmed, recovered, and death cases across multiple countries.

The project combines data preprocessing, exploratory data analysis (EDA), statistical computation, and interactive visualization to extract meaningful insights. Advanced techniques such as rolling averages, correlation analysis, ranking, and pivot tables are applied to understand the pandemic’s progression and impact.

---

# 🎯 2. Objectives
- Perform data cleaning and preprocessing  
- Analyze global COVID trends  
- Compare countries based on key metrics  
- Visualize geographic spread using maps  
- Compute mortality and recovery rates  
- Perform time-series and correlation analysis  
- Identify patterns and insights  

---

# 📂 3. Dataset Description
- **File:** `covid_19_data.csv`  
- **Time Range:** Jan 2020 – May 2021  
- **Coverage:** ~180 countries  

### Key Columns:
- ObservationDate → Date of record  
- Country/Region → Country name  
- Province/State → Region within country  
- Confirmed → Total cases  
- Deaths → Total deaths  
- Recovered → Total recovered  

### Derived Features:
- Active = Confirmed - Recovered - Deaths  
- Mortality Rate (%)  
- Recovery Rate (%)  
- Daily New Cases  
- Rolling Average (7-day)  

---

# 🛠️ 4. Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Jupyter Notebook  

---

# ⚙️ 5. Methodology

### 🔹 Step 1: Data Loading
- Load dataset using `pd.read_csv()`  
- Inspect using `head()`, `info()`  

### 🔹 Step 2: Data Cleaning
- Remove unnecessary columns  
- Handle missing values  

### 🔹 Step 3: Data Transformation
- Convert data types  
- Create new features (Active cases)  

### 🔹 Step 4: Data Aggregation
- Group by country  
- Summarize key metrics  

### 🔹 Step 5: Visualization
- Create maps, charts, and plots  

### 🔹 Step 6: Advanced Analysis
- Compute rates  
- Apply ranking  
- Perform rolling averages  
- Generate pivot tables  

---

# 📊 6. Analysis & Visualizations

### 🌍 Global Choropleth Map
- Visualizes confirmed cases worldwide  
- Highlights high-impact regions  

### 📈 Time-Series Analysis
- Tracks pandemic growth over time  
- Shows trends in cases, deaths, recovery  

### 🔥 Correlation Heatmap
- Displays relationships between variables  

### 📊 Rolling Average
- Smooths daily case fluctuations  
- Identifies waves and peaks  

### 📉 Bar Charts & Rankings
- Compare top countries  
- Analyze performance metrics  

### 📋 Pivot Table
- Monthly case trends across countries  

---

# 🔍 7. Key Insights
- USA, India, and Brazil had highest cases  
- Mortality rates vary significantly across countries  
- Strong correlation between confirmed and deaths  
- Pandemic showed multiple waves globally  
- Rolling averages reveal clearer trends than raw data  

---

# ✅ 8. Conclusion
This project demonstrates how data analysis techniques can be applied to real-world datasets to extract meaningful insights. The use of visualization and statistical analysis helps in understanding the pandemic’s global impact and trends effectively.

---

# 🚀 9. Future Scope
- Integrate vaccination data  
- Apply machine learning forecasting models  
- Normalize data by population  
- Build interactive dashboards  
- Extend dataset for post-2021 analysis  

---

# 📚 10. References
- WHO COVID Dashboard  
- Johns Hopkins Dataset  
- Pandas Documentation  
- NumPy Documentation  
- Seaborn Documentation  
- Plotly Documentation  

---

## 📁 Project Structure

