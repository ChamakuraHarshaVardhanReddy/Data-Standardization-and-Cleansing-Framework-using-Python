# 📊 Data Standardization and Cleansing Framework using Python

## 📌 Project Overview

This project implements a **Data Standardization and Cleansing Framework** to validate, clean, and assess the quality of raw CSV datasets before they are used for analytics or reporting. The framework enforces schema-level validation, standardizes inconsistent data formats, identifies invalid records, and generates a **stakeholder-friendly HTML data quality report**.

The solution reflects real-world data preprocessing workflows commonly used in analytics and data engineering teams to ensure reliable, analytics-ready data.

---

## 🎯 Objectives

- Ingest raw CSV data
- Validate data structure using a predefined JSON schema
- Standardize date and numeric formats
- Identify and isolate invalid or inconsistent records
- Generate a professional HTML data quality report

---

## 🛠️ Tech Stack

- Python 3.11
- pandas
- jsonschema
- HTML & CSS
- GitHub Pages

---


## ⚙️ How It Works

1. **Data Ingestion**  
   Reads raw CSV input using pandas.

2. **Standardization**  
   Converts date columns to a uniform datetime format and ensures numeric fields are properly typed.

3. **Schema Validation**  
   Validates each record against a JSON schema to enforce required fields and data types.

4. **Data Quality Checks**  
   Identifies missing values, invalid numeric ranges, and inconsistent records.

5. **Reporting**  
   Generates a visually rich HTML report summarizing:
   - Total records
   - Invalid records
   - Null value distribution
   - Overall validation status

---

## ▶️ How to Run the Project Locally

### Prerequisites
- Python 3.11.x
- Git

### Install Dependencies
```bash
pip install pandas jsonschema


