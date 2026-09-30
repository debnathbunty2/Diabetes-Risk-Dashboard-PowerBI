# Diabetes Risk Analysis Dashboard (Power BI)

An interactive Power BI dashboard analysing 2,768 patient records to show how age, BMI and glucose relate to diabetes.

![Dashboard](dashboard_screenshot.png)

## Objective
Identify which patient characteristics are most associated with diabetes, and present the findings in a single interactive dashboard.

## Dataset
- **File:** `Healthcare-Diabetes.csv`
- **Size:** 2,768 patients, 9 health metrics and an `Outcome` column (1 = diabetic, 0 = not diabetic)
- **Overall diabetes rate:** 34.4% (952 patients)

## Tools Used
Power BI Desktop, Power Query, DAX

## Data Cleaning (Power Query)
- Replaced invalid zeros with null in Glucose, BloodPressure, SkinThickness, Insulin and BMI (for example, Insulin had 1,330 zero values and SkinThickness had 800)
- Created