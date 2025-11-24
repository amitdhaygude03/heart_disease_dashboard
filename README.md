Heart Disease Analysis Dashboard
Overview
This dashboard provides comprehensive analytics on heart disease patient data, including survival rates, demographic patterns, and clinical indicators.
Key Metrics
Summary Statistics

image : ![4](https://github.com/user-attachments/assets/e9128bf7-e8db-44fa-8a04-da9f2eb334d8)


Survival Rate: 0.68 (68%)
Average Age of Survivors: 58.76 years
Total Survivals: 203 patients
Total Deaths: 96 patients

Dashboard Components
1. Serum Creatinine by Age
A bar chart displaying the distribution of serum creatinine levels across different age groups (ranging from approximately 40 to 100 years). This helps identify:

Age-related kidney function patterns
Potential risk factors by age group
Outliers in creatinine levels

2. Age Distribution by Anaemia and Diabetes
A grouped bar chart showing the sum of ages categorized by:

Anaemia status (0 = No, 1 = Yes)
Diabetes status (0 = No, 1 = Yes)

This visualization reveals comorbidity patterns and helps identify which combinations are most prevalent in the dataset.
3. Survival Rate by Age
A line chart tracking survival rates across different ages (40-90+ years). Key observations:

Shows fluctuations in survival probability with age
Identifies age ranges with higher/lower survival rates
Helps predict outcomes for different age demographics

4. Average Age of Survivors by Diabetes Status
A donut chart comparing:

Diabetes = 0 (No diabetes): Shown in coral/orange
Diabetes = 1 (Has diabetes): Shown in red

This provides a quick visual comparison of average survivor ages between diabetic and non-diabetic patients.
Data Filters
Gender Filter
The dashboard includes a gender toggle allowing analysis by:

Female patients
Male patients

This enables gender-specific pattern analysis across all visualizations.
Use Cases
Clinical Applications

Risk Assessment: Identify high-risk patient profiles based on age, comorbidities, and biomarkers
Treatment Planning: Understand survival patterns to inform intervention strategies
Resource Allocation: Plan healthcare resources based on demographic needs

Research Applications

Analyze correlation between clinical indicators and survival outcomes
Study the impact of comorbidities (anaemia, diabetes) on heart disease prognosis
Investigate age-related survival trends

Technical Details
Data Points
The dashboard analyzes a dataset of 299 patients (203 survivors + 96 deaths) with multiple clinical and demographic variables.
Visualizations

Bar charts for distribution analysis
Line charts for trend analysis
Donut charts for categorical comparisons
Interactive filters for segmented analysis

Interpretation Guidelines
Survival Rate (0.68)
A 68% survival rate indicates that approximately 2 out of 3 patients in this dataset survived their heart disease condition.
Average Survivor Age (58.76)
Survivors average nearly 59 years old, suggesting heart disease affects middle-aged to older adults in this dataset.
Clinical Indicators

Serum Creatinine: Elevated levels may indicate kidney dysfunction, a known comorbidity with heart disease
Anaemia: Can indicate reduced oxygen-carrying capacity, affecting heart function
Diabetes: A major risk factor for cardiovascular complications

Recommendations for Use

Filtering: Use gender filters to identify sex-specific patterns
Correlation Analysis: Cross-reference multiple charts to identify risk factor combinations
Age Stratification: Pay attention to age-related trends in survival and clinical markers
Comorbidity Focus: Analyze how anaemia and diabetes impact outcomes

Future Enhancements
Potential additions to the dashboard could include:

Additional clinical parameters (blood pressure, cholesterol, smoking status)
Time-series analysis showing progression over follow-up periods
Predictive modeling for individual patient risk assessment
Comparative analysis across different treatment protocols
