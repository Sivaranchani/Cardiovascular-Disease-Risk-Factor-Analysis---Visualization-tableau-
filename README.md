# Cardiovascular-Disease-Risk-Factor-Analysis---Visualization-tableau-
An interactive dashboard analysis  of the key drivers of cardiovascular disease


1.0	Introduction & Dataset Details

•	This report outlines the findings from an analysis of a patient dataset aimed at identifying key risk factors for cardiovascular disease (CVD). The analysis was conducted using Tableau to create a series of interactive dashboards for data exploration and insight generation.
•	The dataset, cardio_train.csv, contains records for 70,000 patients. It includes a 
           mix of demographic, physiological, and lifestyle data points.

Key Data Fields:
•	Demographic: id, age (in days), gender (1: Female, 2: Male)
•	Physiological Measurements: height (cm), weight (kg), ap_hi (Systolic Blood Pressure), ap_lo (Diastolic Blood Pressure)
•	Blood Markers: cholesterol (1: Normal, 2: Above Normal, 3: Well Above Normal), gluc (Glucose Levels)
•	Lifestyle Factors: smoke (binary), alco (binary for alcohol consumption), active (binary for physical activity)
•	Target Variable: cardio (1: Presence of CVD, 0: Absence of CVD)
          Data Preparation: Initial data preparation involved creating calculated fields      for Age in Years, Body Mass Index (BMI), and descriptive labels for categorical data (e.g., changing '1' to 'Female'). Data quality issues, such as physiologically impossible BMI values, were identified and filtered out to ensure the accuracy of the analysis.
________________________________________
2.0 Project Objective
The primary objective of this project was to identify and visualize the most significant risk factors contributing to cardiovascular disease. The goal was to create a series of interactive dashboards in Tableau that would allow users to:
1.	Gain a high-level overview of the patient population and CVD prevalence.
2.	Explore the relationships between demographic, clinical, and lifestyle factors and the likelihood of having CVD.
3.	Present these findings in a clear, compelling narrative through a Tableau Story.
________________________________________
3.0 Work Performed: Dashboard Suite

Three distinct dashboards were created to analyze the data from different perspectives, which were then compiled into a cohesive story.

•	Dashboard 1: Overall Risk Factor Analysis: This served as the main dashboard, providing a comprehensive overview. It included KPIs for total patients and CVD rate, and charts visualizing the relationship between age, blood pressure, cholesterol, and CVD.
<img width="1125" height="897" alt="image" src="https://github.com/user-attachments/assets/9072a523-85fe-408b-9996-01569f6a0ffa" />
