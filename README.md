# Task 1 - Excel Data Cleaning & Formatting (Netflix Dataset)

## Overview
This repository contains the **raw dataset** and the **cleaned dataset** for Task 1.  
The dataset was cleaned using **Microsoft Excel** by handling missing values, removing duplicates, and formatting the data properly.

---

## Dataset Used
**Netflix Movies and TV Shows Dataset** (CSV format)

---

## Files Included
- `raw_data.csv` → Original dataset (before cleaning)
- `cleaned_data.csv` → Cleaned dataset (after cleaning)

---

## Data Cleaning Steps Performed
1. **Handled Missing Values**
   - Filled missing values in important text columns (director, cast, country, etc.) with `Unknown`
   - Filled missing rating values with `Not Rated` (where applicable)

2. **Removed Duplicates**
   - Checked and removed duplicates using the `show_id` column

3. **Removed Extra Spaces**
   - Cleaned text fields by removing unwanted extra spaces

4. **Date Formatting**
   - Verified `date_added` format and corrected where needed

5. **Final Review**
   - Ensured cleaned file contains valid records and consistent formatting

---

## Tools Used
- Microsoft Excel / Google Sheets

---

## Output
The final cleaned file is available as:  
✅ `cleaned_data.csv`

---

## Author
**Nithin J R**
