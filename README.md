# customer-personality-cleaning
Data Cleaning and Preprocessing of Customer Personality Analysis dataset (Internship Task 1)
# 🧹 Task 1: Data Cleaning & Preprocessing – Internship Project

### 📁 Dataset Used
Customer Personality Analysis (from Kaggle)  
[Link to dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

---

## 🔧 Tools Used
- Microsoft Excel  
- Excel features: filters, conditional formatting, formulas, table formatting, data validation

---

## ✅ Steps Followed

### 1. Loaded the dataset
- Imported data into Excel
- Fixed column splitting using **Text to Columns** (tab-separated)

### 2. Formatted date values
- Fixed `Dt_Customer` column using **date format**
- Adjusted column widths to show full column names

### 3. Handled Missing Values
- Used **Filter** and **Highlight Cell Rules**
- Found and replaced missing values in `Income` using **Median**

### 4. Standardized text values
- Cleaned inconsistent categories in columns like `Education` and `Marital_Status`
- Example: standardized "Graduation", "Graduate" → "Graduated"

### 5. Renamed all column headers
- All headers converted to **lowercase with underscores**
- Used Find and Replace or edited manually

### 6. Checked and fixed data types
- Converted:
  - `Age` → Number (no decimals)
  - `Dt_Customer` → Date
  - Binary columns (e.g., `Response`, `Complain`) → 0/1 format

### 7. Removed duplicates
- No duplicate rows found using **Remove Duplicates**

### 8. Fixed formatting issues
- Restricted table styling only to actual dataset
- Cleared fill color from empty cells outside the table

---

## 📌 Output
- Cleaned Excel file with:
  - No null values
  - Correct formatting
  - Valid data types
  - Clean column headers

---

## 👩🏻‍💻 Intern Details
- **Name**: VenkateshBabuChunduri
- **Internship Duration**: 30 Days
- **Date**: 07-Apr-2025
