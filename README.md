# ApexPlanet Data Analytics Internship – Task 1
## Data Immersion and Wrangling

### 📌 Project Overview
This project is part of my 60-day Data Analytics Internship at ApexPlanet Software Pvt. Ltd.

The objective of Task 1 is to understand, assess, clean, and transform a sales dataset using Python and Pandas. The project focuses on identifying data quality issues, handling missing values, checking duplicates, standardizing data, and creating new features to prepare the dataset for further analysis.

### 📊 Dataset Description
The dataset contains sales and customer-related information.

- **Total Records:** 1,000
- **Original Columns:** 12
- **Domain:** Sales and Customer Analytics

**Key Columns:**
- Order_ID
- Order_Date
- Customer_ID
- Customer_Name
- Age
- Gender
- City
- Product
- Category
- Quantity
- Unit_Price
- Total_Sales

### 🛠️ Tools and Technologies
- **Python** – Data processing and cleaning
- **Pandas** – Data manipulation and transformation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Data visualization
- **Jupyter Notebook** – Development environment
- **Microsoft Excel** – Dataset inspection

### 🔍 Project Workflow

#### 1. Data Understanding
- Loaded and explored the original dataset.
- Examined the dataset structure, dimensions, and column data types.
- Created a data dictionary explaining each column and its business relevance.

#### 2. Data Quality Assessment
Identified and examined the following issues:
- Missing values in Age and City columns.
- Repeated Order_ID values.
- Inconsistent text formatting.
- Potential outliers in numerical columns.
- Date formatting and data consistency.

#### 3. Data Cleaning
- Handled missing Age values using median imputation.
- Replaced missing City values with "Unknown".
- Standardized text formatting.
- Converted Order_Date into a proper datetime format.
- Investigated repeated Order_ID values instead of automatically deleting potentially valid records.
- Checked data consistency.

#### 4. Feature Engineering
Created additional features to improve the dataset for future analysis:
- Duplicate_Order_ID_Flag
- Order_Year
- Order_Month
- Age_Group

#### 5. Data Validation
- Checked missing values after cleaning.
- Verified duplicate records.
- Validated calculated sales values.
- Reviewed the final dataset structure.

### 📁 Project Structure

```text
Task_1_Data_Cleaning/
│
├── ApexPlanet_DataAnalytics_Dataset.xlsx
├── Cleaned_Sales_Dataset.xls
├── Cleaned_Sales_Dataset.xlsx
├── Data_Dictionary.xls
├── README.md
└── Task1_Data_Cleaning.ipynb
```

### 📈 Final Outcome
Successfully completed the initial data preparation process by exploring, assessing, cleaning, and transforming the sales dataset.

The cleaned dataset is now better structured and ready for further Exploratory Data Analysis (EDA), SQL analysis, and business intelligence tasks.

### 🎯 Key Learnings
- Understanding real-world datasets.
- Identifying and handling data quality issues.
- Performing data cleaning using Python and Pandas.
- Creating meaningful features through feature engineering.
- Validating data before further analysis.
- Maintaining organized project documentation.

### 👩‍💻 Internship Details
**Organization:** ApexPlanet Software Pvt. Ltd.  
**Program:** 60-Day Data Analytics Internship  
**Task:** Task 1 – Data Immersion and Wrangling

---

*This project represents my learning journey in data analytics and my practical application of Python-based data cleaning techniques.*
