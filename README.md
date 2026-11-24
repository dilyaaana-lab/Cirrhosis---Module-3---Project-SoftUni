Liver Cirrhosis & Lab Marker Analysis

What is Cirrhosis?

Cirrhosis is a chronic liver disease characterized by liver damage and scarring, which leads to liver dysfunction. Common causes include liver infections (such as Hepatitis C), long-term alcohol consumption, and medication-induced liver injury.   


Key Laboratory Markers

Blood tests for cirrhosis evaluate liver synthetic function, detoxification capacity, cellular injury, and portal hypertension.   

Albumin (ALB): Low (<35–50 g/L or <3.5–5.0 g/dL) — Indicates impaired synthetic function, which can lead to fluid accumulation (ascites or swelling).

Prothrombin Time (PT) / INR: Prolonged / Elevated — Reflects reduced production of blood-clotting factors, increasing bleeding risk.

Total / Direct Bilirubin (BIL): Elevated — Shows impaired bilirubin clearance, which can cause jaundice.

Platelet Count: Low (<150 × 10⁹/L) — Caused by decreased thrombopoietin production and splenic sequestration due to portal hypertension.

AST & ALT (Aminotransferases): Variable (mildly elevated or normal) — Indicators of ongoing liver cell injury.

Alkaline Phosphatase (ALP) & GGT: Normal to Elevated — Elevations suggest bile duct stress or cholestasis.

Creatinine (CREA) & Sodium: Rising Creatinine / Low Sodium — Monitored for kidney involvement and fluid imbalance (e.g., hepatorenal syndrome).

Total Proteins (PROT): Measured alongside albumin to assess overall protein synthesis.   


AST/ALT Ratio: Calculation & Clinical Meaning
The AST/ALT ratio (also known as the De Ritis ratio) is calculated by dividing the Aspartate Aminotransferase (AST) level by the Alanine Aminotransferase (ALT) level:



 
Clinical Significance: 
An AST/ALT ratio > 2:1 is classically associated with alcohol-related liver disease, whereas ratios < 1 are more typical in non-alcoholic fatty liver disease or chronic viral hepatitis (though the ratio can rise above 1 as cirrhosis progresses).

Data & Methodology

This project combines and standardizes two clinical datasets—Hepatitis C Data (HepatitisCdata.csv) and Indian Liver Patient Data (indian_liver_patient.csv)—to explore lab value relationships and distinguish healthy blood donors from patients with liver disease.   

Statistical Indicators & Tools Used

Libraries: pandas, numpy, scipy.stats, seaborn, and matplotlib.   


Data Preprocessing:
Unit standardization (converting Albumin and Total Proteins from g/dL to g/L, and Bilirubin from mg/dL to µmol/L), gender/category mapping, and missing-value handling (isnull().sum(), dropna()).   

Visualizations:

Boxplots: Used to compare the distribution of liver lab values across age groups (< 30, 30–45, 46–60, 60+) and gender.   


Heatmap Diagrams: Used to visualize correlation matrices between key laboratory markers and disease categories.
