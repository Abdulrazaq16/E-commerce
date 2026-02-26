# E-commerce Analysis

# Obsessive-Compulsive-Disorder-Analysis
This dashboard analyzes e-commerce sales data across different categories, payment methods, customer demographics, and geographic locations.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning Process](#data-cleaning-process)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

---
## Project Overview


This project is intended for educational and research purposes.
This project contains clinical and demographic information about patients diagnosed with Obsessive-Compulsive Disorder (OCD). It includes variables such as patient demographics, symptom duration, types of obsessions and compulsions, Yale-Brown Obsessive Compulsive Scale (Y-BOCS) scores, comorbid diagnoses, and medication history.

This repository documents the dataset and provides a foundation for exploratory data analysis (EDA), statistical modeling, and insights related to OCD patient characteristics and treatment patterns.

> File Name

OCD_PATIENTS_DATASET.csv

> Columns

Patient ID: Unique identifier for each patient
Age: Age of the patient
Gender: Male or Female
Ethnicity: Hausa, Igbo, Yoruba, Fulani
Marital Status: Single, Married, Divorced
Education Level: High School, Some College, College Degree, Graduate Degree
OCD Diagnosis Date: Date of diagnosis
Duration of Symptoms (months): How long symptoms persisted before diagnosis
Previous Diagnoses: Any prior mental health diagnoses (e.g., MDD, PTSD, GAD, Panic Disorder)
Family History of OCD: Yes or No
Obsession Type: e.g., Harm-related, Contamination, Symmetry, Hoarding, Religious
Compulsion Type: e.g., Checking, Washing, Counting, Ordering, Praying
Y-BOCS Score (Obsessions): Severity score for obsessions (0–40)
Y-BOCS Score (Compulsions): Severity score for compulsions (0–40)
Depression Diagnosis: Yes or No
Anxiety Diagnosis: Yes or No
Medications: SSRI, SNRI, Benzodiazepine, None, etc

> Potential Use Cases:

Demographic analysis of OCD patients
Correlation between obsession/compulsion types and Y-BOCS scores
Impact of family history on symptom severity
Comorbidity analysis (depression, anxiety)
Medication usage patterns

---
## Tools Used

- *SMSS* – For data cleaning and transformation  
- *Microsoft Excel* – For further cleaning, Data Collection
- *Power BI* – For Data Visualizations & Reporting 
- *GitHub* – For documentation and version control

---

## Dataset Overview

This project analyzes clinical data from patients with Obsessive-Compulsive Disorder (OCD). The dataset includes patient demographics, symptom types, severity scores, and treatment information.

> What's in the Data?

Patient info: Age, gender, ethnicity, education
OCD details: Symptom types, duration, family history
Scores: Y-BOCS scores for obsessions and compulsions
Other diagnoses: Depression and anxiety
Medications: SSRIs, SNRIs, Benzodiazepines

---
## Data Cleaning Process
 
> Overview

This document outlines the data cleaning process applied to the OCD Patients Dataset to ensure data quality and consistency for analysis.

> Dataset Information

Original File: OCD_PATIENTS_DATASET.csv
Rows: 1,000 patient records
Columns: 17 clinical and demographic variables

> Data Cleaning Steps

1. Initial Assessment
   
Checked dataset structure and dimensions
Identified data types for each column
Located missing values and inconsistencies

3. Missing Values Handling
   
No significant missing values found in this dataset
Strategy: If missing values were present, would use appropriate imputation or removal based on column importance

4. Duplicate Records
   
Checked for duplicate patient entries
No duplicates found in this dataset

5. Data Type Conversion
   
Date Conversion: OCD Diagnosis Date converted to datetime format
Categorical Conversion: Converted 11 columns to category data type for efficiency:
Gender, Ethnicity, Marital Status, Education Level
Previous Diagnoses, Family History of OCD
Obsession Type, Compulsion Type
Depression Diagnosis, Anxiety Diagnosis
Medications

5. Value Standardization
   
Ensured consistent formatting in text fields
Standardize medication names to title case
Verified categorical values match expected categories

6. Data Validation
   
Age Validation: Removed records with age < 10 or > 100 (if any)
Score Validation: Confirmed Y-BOCS scores within a valid range (0-40)
Duration Validation: Verified symptom duration values are reasonable

7. New Feature Creation

Total Y-BOCS Score: Sum of obsession and compulsion scores
Diagnosis Year: Extracted year from diagnosis date
Age Groups: Created categorical age groups for analysis:
0-18, 19-30, 31-45, 46-60, 60+
Duration of symptoms before diagnosis

---
## Dashboard

> Created in Power BI, featuring:

- KPI cards (Average Age of  Patients, Average Duration of Symptoms, Total Number of Patients)
- Total patients diagnosed 
- Avg. symptom duration & patient age 
- Obsession/compulsion severity scores 
- Demographic breakdowns (age group, ethnicity, education level, marital status) 
- Treatment trends (medication effectiveness, family history impact)

![Glassdoor dashboard] (<img width="1228" height="742" alt="ocd 1" src="https://github.com/user-attachments/assets/42bd176f-d7cd-461f-8559-ae2de7eade5c" />)
(<img width="1224" height="745" alt="ocd 2" src="https://github.com/user-attachments/assets/d93c006a-48a1-43af-8e3e-9e8784842b0c" />)
(<img width="1225" height="744" alt="ocd 3" src="https://github.com/user-attachments/assets/3a3ab5b6-7b8b-43b2-a26b-cf31dc870cf7" />)

---
## Conclusion

> Overview

This OCD Patients Dataset provides valuable clinical information for 1,000 patients, offering comprehensive insights into obsessive-compulsive disorder demographics, symptoms, and treatment patterns.

> Key Strengths

Rich Variables: 17 clinical and demographic features
Diverse Representation: Multiple ethnicities, age groups, and education levels
Clinical Depth: Includes Y-BOCS scores, symptom types, and medication history
Clean Structure: Well-organized with minimal missing data

> Potential Analysis Directions

Demographic patterns in OCD presentation
Relationship between obsession/compulsion types
Medication effectiveness across patient groups
Comorbidity analysis with depression/anxiety
Symptom duration before diagnosis trends

> Ideal For

Mental health research
Clinical pattern recognition
Healthcare analytics projects
Academic studies on OCD
Machine learning classification tasks

> Value Proposition

This dataset serves as a robust foundation for understanding OCD characteristics and treatment approaches, making it valuable for researchers, data scientists, and healthcare professionals interested in psychiatric data analysis.




