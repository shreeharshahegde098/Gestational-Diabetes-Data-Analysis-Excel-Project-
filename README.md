🧮 Gestational Diabetes Data Analysis (Excel Project)
📌 Project Overview
This project involves analyzing a healthcare dataset related to Gestational Diabetes Mellitus (GDM) using Microsoft Excel.
The raw data was obtained from Kaggle (CSV format) and transformed into a structured Excel Table for easier analysis.
________________________________________
📊 Dataset Details
The dataset (Gest1.xlsx) contains patient health attributes such as:
•	Age
•	No of Pregnancy
•	Gestation in Previous Pregnancy
•	BMI
•	HDL
•	Family History
•	PCOS
•	Systolic BP (Sys_BP)
•	Diastolic BP (Dia_BP)
•	Hemoglobin
•	Sedentary Lifestyle
•	Prediabetes
•	Class Label (GDM / Non GDM) → Target Variable
•	Derived Features → Age_Basis, OGTT_Round
________________________________________
🛠 Operations Performed
🔹 1. Data Preparation
•	Imported raw Kaggle CSV data into Excel
•	Converted dataset into a Table format for structured analysis
•	Rounded OGTT values to 2 decimal places using =ROUND(cell,2)
•	Added a new feature Age_Basis using =IF(Age>21,"Adult","Child")
🔹 2. Conditional Formatting
•	Highlighted Hemoglobin < 13 in red color
•	Applied color scaling to:
o	Diastolic BP
o	Gestation in Previous Pregnancy
🔹 3. Descriptive Statistics
Using Data Analysis ToolPak, calculated for Price & Quantity (example) and applied same for health data:
•	Mean, Median, Mode
•	Standard Deviation & Variance
•	Range, Min/Max, Count
🔹 4. Pivot Tables & Slicers
•	Created Pivot Tables to summarize pregnancies vs age, GDM vs Non-GDM groups
•	Inserted Slicers to filter data interactively
________________________________________
📈 Key Insights
•	Age classification into Child vs Adult based on >21 rule
•	Hemoglobin deficiencies (<13) highlighted clearly
•	Conditional formatting helped visualize blood pressure & pregnancy history trends
•	Pivot + Slicer enabled dynamic exploration of GDM cases
________________________________________
📂 Files
•	Gest1.xlsx → Processed dataset with cleaning, derived features, formatting, pivots & slicers
________________________________________
🚀 Next Steps
•	Extend to Power BI dashboards for richer visualizations
•	Perform predictive analysis in Python (Pandas, Scikit-learn)
•	Explore deeper statistical comparisons between GDM vs Non-GDM
________________________________________
✅ This project highlights Excel-based data preparation, descriptive statistics, conditional formatting, and interactive analysis with Pivot + Slicer, forming a solid base before moving into Power BI and Python analytics.

