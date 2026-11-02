# Medical Database Analysis (SQL)

**Goal:** Understand patient demographics, admission patterns and doctor workload in a hospital database to support operational decisions.

## Tools
SQL (MySQL)

## Dataset
- Source: Hospital practice database [kaggle]
- Structure: 4 related tables: patients, admissions, doctor, province_names

## Approach
- Queried the 4 related tables using JOINs, subqueries, GROUP BY / HAVING, CASE and UNION.
- Checked data quality by validating admission and discharge dates.

## Key Insights
- Congestive Heart Failure was the top cause of admission.
- About half of admitted patients were readmitted, pointing to a need for stronger follow-up care.
- About **49%** of patients were classified as obese by BMI.

## Data Quality
- Found **62 records** where the discharge date was earlier than the admission date.
- Excluding them, the average hospital stay was about **4.5 days**.

## Files
- `medical sql`: all SQL queries
