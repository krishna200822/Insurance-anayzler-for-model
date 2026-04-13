# 📊 Medical Insurance Cost Analysis (EDA + Statistical Testing)

## 🧠 Overview
This project performs Exploratory Data Analysis (EDA) and statistical feature analysis on a medical insurance dataset to understand factors affecting insurance charges.

The goal is to:
- Identify important features influencing medical costs
- Analyze relationships using statistical methods
- Prepare data for future machine learning models

---

## 📁 Dataset
The dataset contains 1338 rows and 7 columns:

- age – Age of the individual  
- sex – Gender  
- bmi – Body Mass Index  
- children – Number of dependents  
- smoker – Smoking status  
- region – Residential region  
- charges – Medical insurance cost  

---

## 🔍 Steps Performed

### 1. Data Loading & Inspection
- Loaded dataset using pandas
- Checked shape, columns, and data types
- Verified missing values (none found)

---

### 2. Exploratory Data Analysis (EDA)
- Statistical summary using describe()
- Distribution and relationship analysis
- Basic visualization using Seaborn and Matplotlib

---

### 3. Feature Engineering
- Converted categorical variables into encoded features:
  - is_female, is_smoker
  - Region one-hot encoding
  - BMI categories

---

### 4. Correlation Analysis
- Used Pearson Correlation for numerical features
- Measured linear relationship with target (charges)

---

### 5. Chi-Square Test (Categorical Features)
- Converted charges into bins using qcut
- Applied Chi-Square Test of Independence
- Determined feature importance based on p-value

---

## 📈 Key Insights
- Smoking status has a strong impact on insurance charges  
- BMI and age show noticeable correlation  
- Some categorical features have weak statistical significance  

---

## ⚠️ Limitations
- Binning (qcut) reduces precision of continuous data  
- Chi-square test assumptions may not always hold  
- Results are exploratory, not final model conclusions  

---

## 🚀 Future Work
- Build regression models (Linear Regression, etc.)
- Implement feature selection pipelines
- Apply scaling and normalization
- Train ML models and evaluate performance

---

## 🛠️ Tech Stack
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- SciPy  

---

## 🎯 Conclusion
This project builds a strong foundation in:
- Data understanding  
- Statistical reasoning  
- Feature analysis  

It prepares the dataset for machine learning modeling.
