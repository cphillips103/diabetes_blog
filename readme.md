# NHANES Dataset Exploration
## by Christopher Phillips


## Dataset

> The National Health and Nutrition Examination Survey (NHANES) is a program of studies designed to assess the health and nutritional status of adults and children in the United States. The survey is unique in that it combines interviews and physical examinations. NHANES is a major program of the National Center for Health Statistics (NCHS). NCHS is part of the Centers for Disease Control and Prevention (CDC) and has the responsibility for producing vital and health statistics for the Nation.

>The NHANES program began in the early 1960s and has been conducted as a series of surveys focusing on different population groups or health topics. In 1999, the survey became a continuous program that has a changing focus on a variety of health and nutrition measurements to meet emerging needs. The survey examines a nationally representative sample of about 5,000 persons each year. These persons are located in counties across the country, 15 of which are visited each year.

>The NHANES interview includes demographic, socioeconomic, dietary, and health-related questions. The examination component consists of medical, dental, and physiological measurements, as well as laboratory tests administered by highly trained medical personnel.

## Summary of Findings

> The NHANES patient data shows that there is a positive correlation between Diabetes and Weight\BMI, Age, Blood Pressure, and Triglycerides. Less so between Diabetes and Total Cholesterol.


## Key Insights for Presentation

> There is a positive correlation between Age, Weight/BMI, Triglycerides, and Diabetes. Less so between Total Cholesterol and Diabetes. However, after returning to break out HDL and LDL cholesterol, there is a negative association between HDL and Diabetes and a positive association between LDL cholesterol and Diabetes.  

> Along with that, there is an association with Age and Weight, Blood Peassure, Total Cholesterol, and Triglycerides. 

### Were there any interesting or surprising interactions between features?

> I was surprised about the small correlation between Cholesterol and Diabetes, give the association with Diabetes and diet/Weight. However, after returning to break out HDL and LDL cholesterols, it now makes more sense because HDL is considered to be benefitial, while LDL has a negative impact on cardiovascular health for the patient.

In this analysis, we addressed four questions about the NHANES data set and specifically its Diabetes related patient information.
1.	What portion of NHANES study patients have pre-diabetes or full diabetes.
-	Looking at the percentages, 61% of total members did not have diabetes. 27% had pre-diabetes, and 11 had diabetes scores.
2.	Are there differences in demographics that might help predict which population is at a greater risk for developing diabetes?
-	There are positive and negative correlations in the parameters that would be worth exploring. As mentioned above, Age, Weight, Systolic Blood Pressure and Triglycerides appear to have a correlation with Diabetes. HDL has a negative correlation with Diabetes, while LDL has a positive correlation.
3.	How well can we predict an individual's diabetes risk based on their comorbidities?
-	The initial modeling did demonstrate that we can use the data for prediction purpose to better identify those patients that are potentially at risk for developing diabetes.



Credits:
"Type 2." diabetes.org. American Diabetes Association. n.d. Web. (date accessed: 2/18/2021). 2018 AHA/ACC/AACVPR/AAPA/ABC/ACPM/ADA/AGS/APhA/ASPC/NLA/PCNA Guideline on the Management of Blood

Cholesterol: A Report of the American College of Cardiology/American Heart Association Task Force on Clinical Practice Guidelines J Am Coll Cardiol. 2019 Jun, 73 (24) e285–e350

Hypertriglyceridemia Management According to the 2018 AHA/ACC Guideline (see above)

National Health and Nutrition Examination Survey NHANES datasets from 2013-2014 Centers for Disease Control and Prevention • updated 4 years ago (Version 1) from Kaggle.com

Triglycerides and Diabetes https://www.webmd.com/diabetes/high-triglycerides

Type 2 Diabetes | CDChttps://www.cdc.gov › diabetes › basics › type2 https://www.cdc.gov/diabetes/basics/type2.html#:~:text=More%20than%2034%20million%20Americans,adults%20are%20also%20developing%20it.




