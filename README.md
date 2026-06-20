# Hospital Efficiency & Patient Outcome Analytics

## Overview

This project uses a synthetic MIMIC-IV-inspired healthcare dataset to investigate hospital operational efficiency and identify patient characteristics associated with poor outcomes.

The project demonstrates:

* Data Engineering
* Data Cleaning
* SQL Analytics (DuckDB)
* Machine Learning
* Healthcare Operations Analytics
* Data Visualization

---

## Research Questions

### 1. How efficiently is the hospital operating, and where are bottlenecks occurring?

The analysis evaluates:

* Length of Stay (LOS)
* ICU Utilization
* Readmission Rates
* Resource Utilization
* Admission Type Performance

### 2. Which patient characteristics are associated with poor outcomes?

The analysis evaluates:

* Age
* SOFA Score
* Comorbidity Burden
* ICU LOS
* Resource Utilization

using machine learning models.

---

## Dataset

Synthetic MIMIC-IV-inspired dataset:

* 10,000 Patients
* 25,000+ Admissions
* Diagnoses
* Procedures
* Medications
* Laboratory Results
* ICU Stays
* Outcomes

---

## Technologies

* Python
* Pandas
* NumPy
* DuckDB
* SQL
* Scikit-Learn
* Matplotlib
* Google Colab

---

## Project Structure

notebooks/

* 01_Synthetic_MIMIC_Generator.ipynb
* 02_Data_Cleaning_Feature_Engineering.ipynb
* 03_DuckDB_SQL_Analytics.ipynb
* 04_Patient_Outcome_Analytics.ipynb
* 05_Hospital_Operations_Analytics.ipynb

outputs/

* KPI tables
* SQL outputs
* Feature importance outputs

report/

* Healthcare_Analytics_Report.pdf

---

## Key Findings

### Hospital Operations

* Identified operational bottlenecks through LOS, ICU utilization, and readmission analysis.
* Evaluated resource utilization across admission categories.
* Developed efficiency scorecards to compare operational performance.

### Patient Outcomes

* Identified patient characteristics associated with mortality and adverse outcomes.
* Built Logistic Regression and Random Forest models.
* Evaluated model performance using Precision, Recall, F1 Score, and ROC-AUC.

---

## Machine Learning Results

Models:

* Logistic Regression
* Random Forest

Metrics:

* Precision
* Recall
* F1 Score
* ROC-AUC

---

## Author

Bryan Marin Samano
