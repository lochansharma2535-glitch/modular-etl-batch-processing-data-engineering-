 Modular ETL & Batch Processing Pipeline (Titanic Dataset)

 Overview
This project demonstrates a production-style ETL (Extract, Transform, Load) pipeline using Python and Pandas.

It simulates real-world data engineering workflows including:
- Data extraction
- Data cleaning & transformation
- Feature engineering
- Batch processing
- Incremental processing
- Data validation

The Titanic dataset is used as a sample data source.

---

 Project Objectives

- Build a reusable ETL pipeline
- Implement modular data processing functions
- Simulate batch data ingestion
- Perform incremental data processing
- Validate data quality after transformation
- Save processed data for analytics/ML usage

---

  Pipeline Architecture

1. Extraction
   - Load raw CSV data
   - Perform ingestion checks

2. Transformation
   - Handle missing values
   - Remove duplicates
   - Drop irrelevant columns
   - Encode categorical variables
   - Feature engineering (Family Size, Age Groups)

3. Batch Processing
   - Split dataset into batches
   - Process each batch independently
   - Merge cleaned batches

4. Validation
   - Null value checks
   - Duplicate checks
   - Data type verification
   - Range validation

5. Load
   - Save cleaned dataset to CSV

---

 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

Features Implemented

- Modular ETL functions
- Reusable transformation pipeline
- Batch & incremental processing simulation
- One-hot encoding
- Feature engineering
- Data validation checks
- Final warehouse-style dataset generation

---

 Files

- `DE LAB-2.ipynb` – Complete ETL pipeline notebook
- `titanic_cleaned.csv` – Cleaned dataset
- `titanic_final.csv` – Batch processed final dataset

---

Learning Outcomes

This project demonstrates:
- Core data engineering concepts
- Structured pipeline building
- Data quality assurance
- Production-style processing logic

---

 Future Improvements

- Add logging
- Add exception handling
- Convert into CLI-based pipeline
- Deploy using Airflow
- Store in database instead of CSV


L Sharma
Computer Science Engineering Student
