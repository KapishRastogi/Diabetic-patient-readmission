# The Problem Statement
The online fashion retailer has been collecting a vast amount of customer reviews over time. These reviews reflect the diverse range of sentiments that customers have toward our products. However, manually analyzing each review to determine its sentiment can be time-consuming and impractical, given the volume of data. This is where our machine learning model comes in.

# The Solution
The solution involves leveraging the power of natural language processing (NLP) and machine learning. We have developed a sentiment analysis model that can automatically categorize customer reviews into sentiment classes, simplifying the process of understanding how customers feel about our products. This model can not only save time but also provide valuable real-time insights for our business.

# Dataset Description
Encounter ID - Numeric Unique identifier of an encounter
Patient number - Numeric Unique identifier of a patient 
Race Nominal Values- Caucasian, Asian, African American, Hispanic, and other 
Gender Nominal Values- male, female, and unknown/invalid 
Age- Nominal Grouped in 10-year intervals: [0, 10), [10, 20), ..., [90, 100) 
Weight Numeric- Weight in pounds. 
Admission type- Nominal Integer identifier corresponding to 9 distinct values, for example, emergency, urgent,
elective, newborn, and not available 
Discharge disposition- Nominal Integer identifier corresponding to 29 distinct values, for example, discharged to
home, expired, and not available 
Admission source- Nominal Integer identifier corresponding to 21 distinct values, for example, physician referral,
emergency room, and transfer from a hospital 
Time-in hospital Numeric Integer number of days between admission and discharge 
Payer code- Nominal Integer identifier corresponding to 23 distinct values, for example, Blue Cross\Blue
Shield, Medicare, and self-pay
Medical specialty- NominalInteger identifier of a specialty of the admitting physician, corresponding to 84 distinct values, for example, cardiology, internal medicine, family\general practice, and surgeon
Number of lab procedures- Numeric Number of lab tests performed during the encounter 
Number of procedures- Numeric Number of procedures (other than lab tests) performed during the encounter 
Number of medications- Numeric Number of distinct generic names administered during the encounter 
Number of outpatient visits- Numeric Number of outpatient visits of the patient in the year preceding the encounter 
Number of emergency visits- Numeric Number of emergency visits of the patient in the year preceding the encounter 
Number of inpatient visits- Numeric Number of inpatient visits of the patient in the year preceding the encounter 
Diagnosis 1- Nominal The primary diagnosis (coded as first three digits of ICD9); 848 distinct values 
Diagnosis 2- Nominal Secondary diagnosis (coded as first three digits of ICD9); 923 distinct values 
Diagnosis 3- Nominal Additional secondary diagnosis (coded as first three digits of ICD9)
Number of diagnoses Numeric Number of diagnoses entered to the system 
Glucose serum test result- Nominal Indicates the range of the result or if the test was not taken. Values: “>200,” “>300,”
“normal,” and “none” if not measured 
A1c test result- Nominal Indicates the range of the result or if the test was not taken. Values: “>8” if the result
was greater than 8%, “>7” if the result was greater than 7% but less than 8%, “normal” if the result was less than 7%, and “none” if not measured.
Change of medications- Nominal Indicates if there was a change in diabetic medications (either dosage or generic
name). Values: “change” and “no change” 
Diabetes medications Nominal Indicates if there was any diabetic medication prescribed. Values: “yes” and “no” 
24 features for medications- Nominal For the generic names: metformin, repaglinide, nateglinide, chlorpropamide, glimepiride, acetohexamide, glipizide, glyburide, tolbutamide, pioglitazone,
rosiglitazone, acarbose, miglitol, troglitazone, tolazamide, examide, sitagliptin, insulin, glyburide-metformin, glipizide-metformin, glimepiride-pioglitazone, metformin-rosiglitazone, and metformin-pioglitazone, the feature indicates whether the drug was prescribed or there was a change in the dosage. Values: “up” if the dosage
was increased during the encounter, “down” if the dosage was decreased, “steady” if the dosage did not change, and “no” if the drug was not prescribed
Readmitted Nominal- Days to inpatient readmission. Values: “<30” if the patient was readmitted in less than 30 days, “>30” if the patient was readmitted in more than 30 days, and “No” for no record of readmission.
