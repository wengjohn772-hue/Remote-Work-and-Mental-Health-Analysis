# Remote-Work-and-Mental-Health-Analysis
Impact of remote jobs on employees mental health

----

## Remote Work & Mental Health Audit (2026)

----

# Table of Content

----
- [Project Overview](#Project-Overview)
- [Project Task](#project-task)
- [Data Sourcing](#data-sourcing)
- [Preparation Tools](#preparation-tools)
- [Insights](#insights)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

----

##  Project Overview
An end-to-end Power BI analysis of 5,000 employees to identify the drivers of stress and the impact of remote work on mental wellbeing.This analysis was conducted across a population to evaluate the correlation between remote work environments and psychological well-being. The goal is to provide data-driven evidence for refining hybrid work policies and mental health resource allocation.

----

## Project Task
Provide a clear understanding of employee demographics, work arrangements, and mental health patterns. 
Identify key factors influencing stress levels, job satisfaction, and social isolation. 
Offer strategic recommendations for organisations to improve remote work policies based on data-driven insights.

----

## Data Sourcing
Data was obtained from an XLSX file which contain data on employee mental health for remote jobs

----

## Preparation Tools
Power BI was used to leverage this task both analysis and visualizations
<img width="1833" height="923" alt="image" src="https://github.com/user-attachments/assets/ad243f05-4f41-4b61-b0e8-4ecd7514f782" />


----

## Insights
* **Isolation Tipping Point:** Remote workers show a 40% higher frequency of 'High' isolation ratings compared to Hybrid peers.
<img width="807" height="357" alt="image" src="https://github.com/user-attachments/assets/4cfccb57-273f-4195-823f-421c5d27932d" />


* **Meeting Fatigue:** Stress levels spike significantly after a threshold of 10 virtual meetings per week.
<img width="547" height="258" alt="image" src="https://github.com/user-attachments/assets/f9306044-e70c-454a-837e-4eb1f5639428" />

* **Support Gap:** Despite access to mental health resources, high-stress roles (e.g., Sales, Data Science) show lower satisfaction levels, indicating a need for targeted intervention.
<img width="552" height="351" alt="image" src="https://github.com/user-attachments/assets/58999901-7508-4048-8199-5e6919e464df" />


----

##  Technical Implementation
* **Data Modeling:** Optimized Star Schema with 1-to-Many relationships.
* **DAX Measures:** Custom measures for 'Avg Stress', 'Burnout Alert %', and 'Meeting Load'.
* **Visualization:** Custom-designed UI with a silver/gold executive theme for high readability, which include chart to show trend and relationships.

----

##  Dashboard 
<img width="1528" height="853" alt="image" src="https://github.com/user-attachments/assets/f673e314-a4de-42bf-9207-e56ca48e6a41" />

----

<img width="1528" height="847" alt="image" src="https://github.com/user-attachments/assets/6e2f511d-1d2a-45c0-a036-7a5b5811b830" />

## Conclusion
Productivity Change vs. Sleep Quality table, point out that even "High Performers" (those with increased productivity) are showing "Poor" sleep patterns
which affects employees sustainability.
<img width="438" height="208" alt="image" src="https://github.com/user-attachments/assets/3186196a-146e-4f78-b368-bbc997de65bb" />


1. Clone the repo.
2. Open the `.pbix` file in Power BI Desktop.
3. Use the slicers at the top to filter by Industry, Region, or Work Location.
