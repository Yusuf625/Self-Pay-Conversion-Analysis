# Self-Pay Conversion Analysis

This project analyses self-pay patient enquiries to understand the factors that influence conversion from enquiry to surgery.

Using a synthetic private healthcare dataset, the analysis explores how operational factors — such as consultation delay, procedure type, hospital site, and consultant performance — impact both conversion rates and revenue outcomes.

---

## Project Focus

The analysis investigates key drivers of self-pay conversion performance, including:

- Patient funnel progression from enquiry to consultation to surgery
- Differences in performance across hospital sites
- Revenue contribution by procedure type
- Consultant-level conversion performance
- The impact of consultation delay on likelihood of conversion

Rather than focusing on data cleaning, this project centres on structuring the dataset to enable meaningful operational analysis and performance measurement.

---

## Tools Used

- Excel – data processing, pivot table analysis, and modelling layer
- Google Sheets – exploratory analysis
- Looker Studio – dashboard visualisation
- GitHub – project documentation and version control

---

## Project Workflow

This project follows a structured analytical workflow:

1. **Data Preparation**
   - A synthetic private healthcare group dataset was generated to simulate self-pay patient enquiries and surgical pathways.

2. **Data Processing**
   - Additional analytical fields were created in the processed dataset to support analysis, including:
     - `funnel_stage`
     - `consultation_delay_days`
     - `delay_bucket`
     - `revenue_per_enquiry`

3. **Exploratory Analysis**
   - Pivot tables were used to analyse:
     - Patient funnel progression
     - Hospital performance
     - Procedure revenue contribution
     - Consultant conversion performance
     - The impact of consultation delays on conversion

4. **Insight Generation**
   - Key operational insights were documented in:

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

- Structuring raw operational data for analytical use
- Building funnel analysis and performance metrics using spreadsheet tools
- Linking operational healthcare activity to revenue outcomes
- Translating exploratory analysis into practical business insight
