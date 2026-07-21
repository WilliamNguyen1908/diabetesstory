# Increased Risk of Heart Disease in the Diabetes Mellitus Patient Population
 
An exploratory data analysis of how diabetes (primarily type 2) compounds cardiovascular risk — tracing the path from blood glucose and HbA1c through cholesterol, blood pressure, and BMI to heart disease.
 
📄 Full write-up: [Increase risk of heart disease in diabetes mellitus patient population](https://medium.com/@wpnguyen_94917/increase-risk-of-heart-disease-in-diabetes-mellitus-patient-population-42b2d2b16693)

📁 [dataset](https://drive.google.com/file/d/1JLJT0oGoW4vtl6KfDtA7CMM7jSEysDb0/view?usp=drive_link)
 
## Overview
 
Diabetes rarely stays contained to blood sugar alone — over time it raises the risk of cardiovascular disease, kidney disease, and other complications. This project uses patient-level data to trace how diabetes drives up heart disease risk specifically, examining the relationships between:
 
- **Family history** and diabetes likelihood
- **HbA1c** (average blood glucose over 2–3 months) and glucose levels
- **Cholesterol** (LDL vs. HDL) and glucose
- **Blood pressure** and glucose, comparing diabetic vs. non-diabetic patients
- **BMI** and glucose, comparing diabetic vs. non-diabetic patients
## Tech Stack
 
- **SQL** — querying and aggregating patient records
- **Python / pandas** — data cleaning, transformation, and analysis
## Key Findings
 
**Family History**
Patients with a family history of diabetes are more likely to develop it themselves — consistent with the strong genetic component of type 2 diabetes.
 
**HbA1c & Glucose**
Non-diabetic patients show low, steady HbA1c even as glucose fluctuates. Diabetic patients show HbA1c climbing sharply alongside glucose, frequently crossing the 6.5% diagnostic threshold — a sign of poorly controlled blood sugar that, left unmanaged, damages the heart, kidneys, nerves, and eyes over time.
 
**Cholesterol (LDL/HDL)**
As glucose rises, LDL ("bad" cholesterol) trends upward while HDL ("good" cholesterol) trends downward. Chronic high blood sugar drives insulin resistance, which disrupts lipid regulation — more LDL to clog arteries, less HDL to clear it out.
 
**Blood Pressure**
Glucose and blood pressure rise together in both diabetic and non-diabetic patients, but the relationship is steeper in diabetics — elevated glucose contributes to vasoconstriction, fluid retention, and arterial inflammation, compounding cardiovascular strain.
 
**BMI**
Glucose and BMI are positively related in both groups, but the trend is markedly steeper in diabetic patients, with nearly half of diabetic patients above a BMI of 30 (obese) versus mostly under 30 in non-diabetics — tying insulin resistance directly to weight gain and, in turn, back to blood pressure and cholesterol risk.
 
## Recommendations
 
Steps toward reducing heart disease risk in diabetic patients:
 
- Take diabetes medication as prescribed
- Plan and manage daily meals
- Exercise ~30 minutes most days of the week
- Manage blood pressure and cholesterol
- Avoid alcohol and tobacco
- Get regular heart checkups


## Dataset
 
Patient-level records including family history of diabetes, blood glucose, HbA1c, LDL/HDL cholesterol, blood pressure, and BMI, split between diabetic and non-diabetic patients.
 
## Author
 
**William Nguyen**
[Medium](https://medium.com/@wpnguyen_94917)
