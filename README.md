# Diabetes-Readmission-Analysis
An exploratory analysis on factors affecting 30-day hospital readmission  among patients with diabetes.
## Project Overview
Analysis of 87,000+ patient records from 130 US hospitals to identify factors associated with 30-day readmissions among diabetic patients.

**Key Finding:** Disease severity and poor diabetes control are the primary drivers of readmission risk

## Key Questions
1. Does patient age correlate with readmission risk?
2. Does time spent on admission affect readmission rate?
3. What role does admission type play in readmissions?
4. Are medication changes during hospitalization associated with readmission rates?

## Key Insights
**Disease Severity Pattern:**
-Patients on diabetes medication: 48% readmission rate with higher <30 rates vs 41% for those not on medication.  
-Medication change during hospitalization: 48.7% vs 44.2% for stable regimens.  
-Higher medication counts: 17 meds (readmitted) vs 16 meds (not readmitted).  

**Clinical Implications:**
- Risk stratification should focus on severity markers (emergency admission, complex medication regimens, treatment changes)
- Targeted interventions for high-severity patients could significantly reduce readmission burden
- Universal discharge protocols less effective than severity-stratified approaches

 **Proposed Risk Stratification Framework:**

HIGH RISK: Emergency admissions + medication changes + >16 medications
- Intensive discharge planning
- 72-hour post-discharge follow-up
- Assigned care coordinator
- Weekly follow-up for first month

MODERATE RISK: Urgent admissions OR elderly OR moderate medication burden (10-16)
- Enhanced education and pharmacy consult
- 7-14 day follow-up
- Phone check-ins at 3 and 7 days

LOW RISK: Elective admissions + stable regimens + <10 medications
- Standard discharge protocol
- 2-3 week follow-up with primary care physician

## Tools & Technologies
- **Python:** pandas, matplotlib
- **Platform:** Jupyter Notebook
- **Dataset: **[Diabetes 130-US Hospitals](https://www.kaggle.com/datasets/brandao/diabetes) (100k+ records, 1999-2008)

##  Project Structure
├── diabetes-readmission-analysis.ipynb (Main analysis notebook)
├── diabetic_data.csv (Dataset)
├──IDS_mapping.csv (Mapping of observations in different variables)
└── README.md

## How to Run
1. Clone this repository
2. Install required packages: `pandas`, `matplotlib`, 
3. Open the Jupyter notebook
4. Run all cells

## About This Project
This analysis is a first project as part of my transition from medicine into data analytics. As a medical intern developing data skills, I'm passionate about using analytics to improve patient outcomes and healthcare delivery.

## Connect With Me
- LinkedIn: https://www.linkedin.com/in/chiomaozioko/
- Email: chiomaozioko2@gmail.com
