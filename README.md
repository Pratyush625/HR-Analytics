# HR-Analytics

## 📝 PySpark Project Steps
### Source: Kaggle:[https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists]
### Databricks link: [https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/942461825785439/238116055874869/7969322971623369/latest.html]



This guide outlines the steps followed in the project for data processing using PySpark in Databricks.

---

### 📌 Step 1: Loading & Understanding Data
- ✅ Reading CSV files in Databricks  
- ✅ Checking schema and data types  

---

### 📌 Step 2: Data Cleaning & Transformation
- ✅ Renaming columns for better clarity  
- ✅ Converting categorical values into numerical format  
- ✅ Handling NULL values using `fillna()`, `dropna()`  

---

### 📌 Step 3: Working with DataFrames
- ✅ Using `filter()`, `sort()` operations  
- ✅ Performing column operations like `withColumn()`, `alias()`, and `cast()`  

---

### 📌 Step 4: Advanced PySpark Functions
- ✅ Using `explode()`, `collect_list()`, `pivot()`, `when()`, `otherwise()`  
- ✅ String functions: `initcap()`, `upper()`, `lower()`  
- ✅ Date functions: `current_date()`, `datediff()`, `date_add()`, `year()`, `month()`  

---

### 📌 Step 5: Joins & Data Merging
- ✅ Inner, Left, Right & Outer Joins  
- ✅ `union()` & `unionByName()` for combining datasets  

---

### 📌 Step 6: Window Functions & Ranking
- ✅ Using `rank()`, `dense_rank()`, and cumulative sum  
- ✅ Partitioning and ordering data efficiently  

---

### 📌 Step 7: User Defined Functions (UDFs)
- ✅ Writing custom functions in PySpark  
- ✅ Applying UDFs to transform and clean data  

---

### 📌 Step 8: Writing & Saving Data
- ✅ Writing datasets in CSV, JSON, ORC, and Delta formats  
- ✅ Overwriting, appending, and handling errors while saving  

---
