# edufin-loan-data-engineering
End-to-end loan data engineering pipeline using PySpark
EduFin Loan Data Engineering Project

📌 Overview

An independently built, end-to-end loan data engineering project using Python and PySpark.

The project demonstrates how raw loan data can be validated, transformed, analyzed, and converted into a curated dataset suitable for downstream analytics.

Note: This is an independently built EduFin-style portfolio project. It is not presented as the official SkillAI case study.

⸻

🏗️ Pipeline

Raw Loan Data
      ↓
PySpark DataFrame
      ↓
Data Quality Validation
      ↓
Data Transformation
      ↓
Risk Classification
      ↓
Business Aggregation
      ↓
Curated Dataset
      ↓
CSV + Parquet

⸻

🛠️ Technologies

* Python
* PySpark
* Apache Spark
* Google Colab
* CSV
* Parquet
* GitHub

⸻

🔍 Data Quality Checks

The pipeline performs:

* Missing-value validation
* Duplicate record validation
* Duplicate loan ID validation
* Loan amount validation
* Monthly income validation
* Credit score validation

⸻

⚙️ Transformations

Loan Exposure Ratio

Loan Amount / (Monthly Income × Loan Term)

Monthly Loan Burden

Loan Amount / Loan Term

Risk Classification

Loans are classified into:

* High Risk
* Medium Risk
* Low Risk

based on credit score and loan exposure ratio.

⸻

📊 Business Analysis

The project analyzes:

* Overall loan portfolio statistics
* Default rate
* City-level default rates
* Employment-type default rates
* Risk-category distribution
* Total loan exposure

⸻

📦 Output

The final curated dataset is generated in:

* CSV
* Parquet

The Parquet output is also read back into PySpark to validate the generated dataset.

⸻

📚 PySpark Concepts Practiced

* SparkSession
* DataFrames
* Schema inspection
* select()
* filter()
* withColumn()
* when()
* groupBy()
* agg()
* count()
* sum()
* avg()
* round()
* Sorting
* CSV writing
* Parquet writing
* Reading Parquet
* Data validation

⸻

📁 Project Structure

edufin-loan-data-engineering/
│
├── README.md
│
└── EduFin_Loan_Data_Engineering_PySpark.ipynb

⸻

🎯 Project Outcome

This project demonstrates an end-to-end PySpark workflow covering data validation, transformation, feature engineering, risk classification, aggregation, and curated data generation.

The project was built as part of my transition toward a Data Engineering role.