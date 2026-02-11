# Self-Pay Conversion Analysis

This project explores enquiry-to-surgery conversion performance using a synthetic private healthcare dataset.

The aim was to understand how operational factors — such as consultation delay, procedure type, and hospital performance — influence both conversion rates and revenue outcomes.

---

## Project Focus

The analysis looks at:

- Overall conversion from enquiry to surgery  
- Differences in performance across hospitals and consultants  
- Revenue concentration by procedure  
- The impact of consultation delay on likelihood of conversion  

Rather than focusing on data cleaning, this project centres on structuring the data for meaningful operational analysis.

---

## Tools Used

- Excel – creation of derived metrics and modelling layer  
- Google Sheets – exploratory analysis  
- Looker Studio – dashboard visualisation  

---

## Data Structure

The repository follows a simple workflow:

- `data/raw/` – original synthetic dataset  
- `data/processed/` – analysis-ready dataset with engineered fields  
- `dashboards/` – dashboard link and screenshots  
- `insights/` – written findings and business interpretation  

---

## Derived Fields Added

To support structured analysis, the processed dataset includes:

- `funnel_stage`
- `consultation_delay_days`
- `delay_bucket`
- `revenue_per_enquiry`

These fields were created to enable clearer segmentation and performance measurement.

---

## What This Project Demonstrates

- Structured data modelling using spreadsheet tools  
- Funnel analysis and KPI development  
- Linking operational behaviour to financial outcomes  
- Translating data into practical business insight  
