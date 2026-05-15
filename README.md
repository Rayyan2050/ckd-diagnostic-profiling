# ckd-diagnostic-profiling
CKD Diagnostic Profiling
The study utilizes a robust dataset of 20,537 patients consisting of 43 biomarkers and clinical indicators. The dataset is categorized into 5 diagnostic classes representing different stages of kidney health: No_Disease, Low_Risk, Moderate_Risk, High_Risk, and Severe_Disease/CKD. CKD affects 850 million people globally, often diagnosed only after losing 50% of function
the data dictionary is at https://github.com/Rayyan2050/ckd-diagnostic-profiling/commit/772634b248f4522f6e180ad9fc2fcd71907dab4b  the clinical data dictionary is created from scratch using domain knowledge by me.
the sample of the data ca be accessed here at https://github.com/Rayyan2050/ckd-diagnostic-profiling/commit/fe15c8c4b8b1a46d324d76492deb7e331f313c4c
**Key Findings & Model Performance**
Top 3 Biomarkers: Blood Pressure 0.000581991
<img width="211" height="22" alt="image" src="https://github.com/user-attachments/assets/8d5b3165-981e-48e4-8e4e-50ae0b6c1c86" />
Blood Glucose 0.01270973
<img width="211" height="22" alt="image" src="https://github.com/user-attachments/assets/983ad963-f5a3-4342-bc1e-ba8bb6104b14" />
, and Serum Creatinine 0.004139471
<img width="144" height="22" alt="image" src="https://github.com/user-attachments/assets/18e8ac03-8683-4bf6-8e55-bea0e0f7ac47" /> 
Engineered Features: CKD Staging (G1–G5): Categorizes the progression of Chronic Kidney Disease into five distinct stages (G1 to G5) based on kidney filtration efficiency and eGFR measurements.

Dual-Risk Comorbidity Flag: A composite indicator that identifies patients suffering from both Hypertension (HTN) and Diabetes (DM), flagging them as high-risk for advanced renal complications.

BP Category: Groups patients into specific blood pressure classifications (e.g., Normal, Elevated, Hypertension) to track cardiovascular impact on kidney health.

Glucose Category: Categorizes patients by blood sugar levels to monitor metabolic risks and their correlation with renal decline.

Age Group: Segments the patient population into demographic brackets to analyze age-related trends in disease prevalence and progression.

Creatinine Flag: An automated indicator that flags abnormal serum creatinine levels, serving as a primary signal for impaired kidney function.

CKD Risk Score: A multi-factor diagnostic metric that aggregates various clinical parameters to provide a weighted probability of Chronic Kidney Disease presence.
Performance Metrics: CKD Recall - 7.07%, low risk % - 10%
Technical Stack & AssetsTools Used: Excel and Power BI are my primary tools.
Visual Gallery: 
<img width="763" height="421" alt="DB 5" src="https://github.com/user-attachments/assets/97394cce-fe9f-47e6-a189-c220533ac9b5" />
<img width="757" height="382" alt="DB 4" src="https://github.com/user-attachments/assets/f9fa70d2-0af7-4b2b-9bbf-9b436b094a9d" />
<img width="768" height="410" alt="DB 3" src="https://github.com/user-attachments/assets/295d991d-4968-4da3-8e9a-d380bc7b5f59" />
<img width="763" height="403" alt="DB 2" src="https://github.com/user-attachments/assets/1bd23f7c-4f25-485c-a492-ceb68d720ef4" />
<img width="751" height="398" alt="DB 1" src="https://github.com/user-attachments/assets/cd73541f-d331-41af-8b42-798dcf1fa1e3" />

Limitations: A cross-sectional design rule-based model versus Machine Learning.
Clinical Disclaimer: These findings are for research and analytical purposes only and not for actual patient diagnosis.
Project Directory Overview/dataContains the raw and processed datasets. This includes the initial patient records and the cleaned, feature-engineered CSV/Excel files that power the analysis, such as the tables containing the CKD Staging and Comorbidity Flags./reportsIncludes formal documentation and static exports. You will find the PDF export of the Power BI report, project summaries, and detailed documentation explaining the methodology behind the $16.34\%$ CKD Recall performance./dashboardHouses the interactive visualization files. This contains the primary Power BI file (.pbix), allowing recruiters to explore the live clinical features, performance metrics, and patient risk distributions in real time.Contact InformationEmail: **abuabdulrahman4@gmail.comPhone: +2347066591002**
