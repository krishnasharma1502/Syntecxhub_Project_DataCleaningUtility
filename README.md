# 🧹 Data Cleaning Utility  
Syntecxhub Data Science Internship – Week 1  

---

## 📌 Project Overview

This project implements a **modular data cleaning pipeline** using Python and Pandas.  
It automates common preprocessing tasks required before performing analysis or machine learning.

The utility is reusable and designed to work on structured tabular datasets.

---

## 🚀 Features

- ✅ Column name standardization  
- ✅ Automatic date column detection & conversion  
- ✅ Duplicate row removal  
- ✅ Missing value handling  
  - Numeric → Median  
  - Categorical → Mode  
- ✅ Cleaning summary report generation  
- ✅ Export cleaned dataset to CSV  

---

## 🛠️ Tech Stack

- Python 3.x  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## 📂 Project Structure
Data_Cleaning_Utility/
│
├── data/
│ └── raw_data.csv
│
├── cleaned_output/
│ ├── cleaned_data.csv
│ └── cleaning_report.txt
│
└── cleaning_utility.ipynb

---

## 🔄 Cleaning Pipeline

The project is built using modular functions:

```python
standardize_columns()
convert_dates()
remove_duplicates()
handle_missing()
clean_data()
The clean_data() function acts as a unified pipeline that applies all preprocessing steps sequentially.
📊 Cleaning Report

After execution, the utility generates:

Original dataset shape

Cleaned dataset shape

Number of rows removed

Total columns

Missing values after cleaning

🎯 Outcome

The cleaned dataset contains:

✔ Standardized columns

✔ Proper date formats

✔ No duplicates

✔ No missing values

It is ready for downstream analytics or machine learning workflows.

📌 Future Improvements

Add logging system

Convert to CLI tool

Package as reusable Python module

Add automated validation tests

👤 Author

Krishna Sharma
B.Tech – Artificial Intelligence & Data Science
Syntecxhub Data Science Intern

⭐ If you found this project useful, feel free to star the repository.

