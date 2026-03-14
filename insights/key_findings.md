# Key Findings

## Overview

This project analyses a synthetic private healthcare dataset to understand what drives conversion from **self-pay enquiry to surgery**.

The dataset contains **650 patient enquiries**, of which **177 converted to surgery**, generating **£920,200 in revenue**.  
This represents an overall **conversion rate of 27%**.

The analysis focuses on identifying operational factors that influence conversion, including consultation timing, hospital performance, procedure mix, and consultant activity.

---

## 1. The Largest Drop-Off Occurs Before Consultation

Out of **650 enquiries**, only **414 progressed to consultation**, while **236 enquiries (36%) did not reach consultation at all**.

Once a consultation takes place, the likelihood of conversion increases significantly.  
Among the **414 patients who attended consultation, 177 proceeded to surgery**, giving a **consultation-to-surgery conversion rate of 43%**.

This suggests the biggest opportunity to improve performance is **getting more enquiries to consultation**, rather than improving post-consultation conversion.

---

## 2. Conversion Performance Varies Across Hospital Sites

Conversion performance differs across hospital locations.

| Hospital | Enquiries | Conversions | Conversion Rate | Revenue |
|---|---|---|---|---|
Hospital A | 152 | 33 | 22% | £143,800 |
Hospital B | 181 | 46 | 25% | £241,500 |
Hospital C | 166 | 47 | 28% | £245,500 |
Hospital D | 151 | 51 | **34%** | **£289,400** |

Hospital D achieved both the **highest conversion rate and the highest total revenue**, despite having a similar enquiry volume to the other sites.

This suggests there may be operational practices at this site that support stronger conversion outcomes. However, external factors such as location, patient demographics, or local demand may also influence performance and should be considered when interpreting these differences.

---

## 3. Revenue Is Driven by a Small Number of High-Value Procedures

Total revenue in the dataset is heavily concentrated in a small number of higher-value procedures.

| Procedure | Revenue |
|---|---|
| Knee Replacement | £264,600 |
| Hip Replacement | £212,500 |
| Gallbladder Removal | £201,500 |
| Cataract Surgery | £68,200 |
| Hernia Repair | £67,200 |
| Colonoscopy | £64,800 |
| Endoscopy | £41,400 |

Joint replacement procedures generate the largest share of revenue despite representing a smaller proportion of overall cases. This reflects the significantly higher procedure price compared with diagnostic procedures such as colonoscopy and endoscopy.

---

## 4. Consultant Conversion Performance Is Relatively Similar

Consultant conversion rates fall within a fairly narrow range.

| Consultant | Enquiries | Conversions | Conversion Rate | Revenue |
|---|---|---|---|---|
Dr Michael Thompson | 101 | 30 | **30%** | £149,100 |
Dr Sarah Lewis | 110 | 32 | 29% | £189,100 |
Dr Aisha Khan | 118 | 32 | 27% | £117,200 |
Dr Daniel Wright | 107 | 29 | 27% | £174,100 |
Dr Priya Patel | 110 | 28 | 25% | £141,900 |
Dr James Carter | 104 | 26 | 25% | £148,800 |

While some variation exists, consultant performance appears broadly consistent.

This suggests that **site-level processes or operational factors may play a larger role in overall conversion performance than individual consultants.**

---

## 5. Faster Consultations Are Linked to Higher Conversion

Consultation timing appears to influence conversion outcomes.

| Consultation Delay | Enquiries | Conversions | Conversion Rate |
|---|---|---|---|
0–7 Days | 87 | 36 | 41% |
8–14 Days | 101 | 48 | **48%** |
15+ Days | 226 | 93 | 41% |
No Consultation | 236 | 0 | 0% |

Patients who receive consultations within **two weeks of enquiry convert at significantly higher rates than the overall average conversion rate of 27%**.

This indicates that **reducing consultation waiting times may help improve overall conversion performance.**

---

## Summary

The analysis highlights several operational patterns in the self-pay pathway:

- A large proportion of enquiries never reach consultation.
- Conversion performance varies across hospital sites.
- Revenue is concentrated in a small number of high-value procedures.
- Consultant conversion rates are relatively consistent.
- Faster consultation scheduling is associated with improved conversion outcomes.

Overall, the results suggest that improving **enquiry handling and consultation booking efficiency** may provide the biggest opportunity to increase both conversion rates and revenue.


While the dataset provides useful insight into conversion patterns, it is based on a synthetic dataset and does not capture all real-world factors that may influence outcomes, such as geographic location, patient demographics, or local market demand.
