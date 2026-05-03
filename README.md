# Module 10 Assignment: Data Manipulation and Cleaning with Pandas

**UrbanStyle Customer Data Cleaning**

## Description
This project focuses on the critical first step of any data analysis: data cleaning and preparation. Using a simulated dataset for "UrbanStyle" (a retail brand), the script takes "messy" raw data—containing inconsistent date formats, currency symbols, duplicate records, and missing values—and transforms it into a high-quality, analysis-ready format. The final output provides key business insights into customer loyalty and revenue distribution.

## Files Included
* `urbanstyle_cleaning.py`: The Python script containing the data loading, cleaning logic, and report generation.
* `README.md`: Documentation for the repository.

## What I Practiced
In this assignment, I practiced the "detective work" required to handle real-world data issues using Python:
* **Missing Value Imputation:** Strategically filling gaps in the data using medians for numerical values and forward-fill logic for time-based entries.
* **Regular Expressions (Regex):** Using regex to strip currency symbols and commas from strings to convert them into usable floats, and standardizing phone numbers into a uniform `(XXX) XXX-XXXX` format.
* **String Standardization:** Cleaning text data by correcting mixed casing in names and categories (e.g., converting "JESSICA" to "Jessica" and "womenswear" to "Womenswear").
* **Data Type Enforcement:** Managing mixed date formats (e.g., `YYYY-MM-DD` vs `MM/DD/YYYY`) and ensuring columns were properly typed as datetime or integer.
* **Feature Engineering:** Creating derived business metrics like `average_purchase_value` and `days_since_last_purchase` to add depth to the analysis.
