# 911_Calls_Analysis

#### Table of contents
--------------------------
- [Project Overview](#Project_Overview)
  
- [Data Source](#Data_Source)
  
- [Tools](#Tools)
    
- [Data Cleaning / Preparation](#Data_Cleaning_/_Preparation)
    
- [List of Abbreviations](#List_of_Abbreviations)
    
- [Exploratory Data Analysis](#Exploratory_Data_Analysis)
    
- [Findings / Results](#Findings_/_Results)
    
- [Recommendations](#Recommendations)  





### Project Overview
This project explores emergency 911 call data to identify temporal, categorical, and geographic trends.
The analysis focuses on:
•	Understanding the distribution of calls by type (EMS, Fire, Traffic).

•	Examining seasonal and hourly variations in call volumes.

•	Identifying geographic hotspots of emergency activity.

•	Highlighting patterns that can inform operational planning and public safety strategies.

### Data Source
Dataset: [Emergency - 911 Calls](https://www.kaggle.com/datasets/mchirico/montcoalert)

Key Features: lat, lng, title, timeStamp, zip, twp, desc.

### Tools

Programming Language: Python

Libraries Used:

Pandas: Data cleaning and manipulation.

NumPy: Numerical operations and array handling.

Matplotlib & Seaborn: Static visualizations for trends and distributions.

Environment: Jupyter Notebook for iterative exploration and documentation.


### Data Cleaning/Preparation
The initial data cleaning / preparation was initiated below:
•	Converted timestamps into datetime format.

•	Extracted features: Hour, Day of Week, Month.

•	Standardized categories (EMS, Fire, Traffic).

•	Removed duplicates and handled missing values.

•	Created subsets for category‑specific analysis.

### List of Abbreviations

•	EMS: Emergency Medical Services

•	twp: Township

•	zip: Zip Code

### Exploratory Data Analysis (EDA)
Below were the analytics insight questions below:

1: Calls by Category.

2: Calls by Day of Week.

3: Calls by Hour of Day.

4: Monthly Trends.

5: Geographic Hotspots.

The analysis of 911 call data reveals distinct patterns in emergency service demand. Understanding these trends is essential for resource allocation, staffing, and long term planning. The insights below highlight the most critical operational drivers and their implications.

I.	EMS calls dominate (70%): Medical emergencies are the primary driver of demand, requiring sustained investment in EMS capacity.

II.	Fridays and Saturdays peak: Weekend surges necessitate flexible staffing models to ensure adequate coverage.

III.	Peak hours: 5–9 PM: Evening shifts should be prioritized for resource allocation to handle higher call volumes.

IV.	Winter months show higher volumes: Seasonal preparedness, including winter surge planning, is critical for operational resilience.

V.	Certain townships are hotspots: Geographic targeting of resources can improve response times and efficiency.

VI.	EMS growth steady, Fire stable, Traffic seasonal: Long‑term planning should prioritize EMS expansion, while maintaining stable fire services and adapting to traffic seasonality.

### Findings / Results
The exploratory data analysis of 911 call records reveals several critical operational patterns that have direct implications for emergency service management:
1.	EMS Calls as the Primary Driver
•	Approximately 70% of all calls are related to medical emergencies.
•	This dominance underscores the need for sustained investment in EMS resources, personnel, and infrastructure, as they represent the largest share of demand.

3.	Temporal Peaks in Demand
•	Day of Week: Call volumes rise significantly on Fridays and Saturdays, indicating weekend surges.
•	Time of Day: The 5–9 PM window consistently shows the highest activity, highlighting evening hours as the most resource-intensive period.
•	These temporal trends suggest that staffing models must be flexible, with additional personnel allocated to weekends and evening shifts.

5.	Seasonal Variations
•	Winter months record higher call volumes compared to other seasons.
•	This seasonal spike emphasizes the importance of preparedness measures such as surge staffing, equipment readiness, and winter-specific emergency protocols.

7.	Geographic Concentration
•	Certain townships emerge as hotspots with disproportionately high call volumes.
•	Targeted resource deployment in these areas can improve response times and operational efficiency.

9.	Category Trends Over Time
•	EMS: Steady growth, reinforcing its role as the dominant service category.
•	Fire: Stable demand, requiring consistent but not expanding resources.
•	Traffic: Seasonal fluctuations, suggesting the need for adaptive strategies aligned with traffic patterns.
•	These trends indicate that long-term planning should prioritize EMS expansion while maintaining stable fire services and adopting flexible approaches for traffic-related incidents.

### Recommendations

I. Expansion of EMS Capacity: Given that EMS calls account for approximately 70% of total demand, it is essential to prioritize investment in EMS infrastructure, personnel, and advanced medical equipment. Ambulance fleets should be expanded, and mobile EMS units considered, to ensure adequate coverage as demand continues to grow steadily.

II. Optimization of Staffing Models: Staffing schedules must be aligned with observed demand peaks. Fridays and Saturdays consistently show higher call volumes, while the 5–9 PM window represents the busiest hours of the day. Flexible rostering systems, overtime pools, and dynamic shift adjustments should be implemented to guarantee sufficient coverage during these critical periods.

III. Seasonal Preparedness Planning: The winter months exhibit a clear surge in emergency calls, necessitating proactive seasonal preparedness. This includes temporary staffing arrangements, rigorous equipment maintenance, and coordination with hospitals to manage increased patient inflows. Vehicles should be winter ready, and essential supplies stockpiled to ensure resilience during seasonal spikes.

IV. Geographic Resource Deployment: Certain townships emerge as hotspots for emergency calls, requiring targeted resource allocation. Establishing satellite EMS stations or deploying mobile response units in these areas will reduce response times and improve operational efficiency.

V. Category Specific Strategic Focus: Distinct service categories demand tailored approaches. EMS requires expansion and sustained investment to meet its consistent growth. Fire services remain stable, suggesting that resources should be maintained at current levels with a focus on efficiency. Traffic incidents, however, fluctuate seasonally, and adaptive strategies such as increased patrols or coordination with traffic management agencies should be adopted during peak periods.

VI. Integration of Predictive Analytics: To enhance responsiveness, predictive analytics should be employed to anticipate demand surges based on historical patterns. Real time dashboards and monitoring systems will allow for dynamic adjustments in staffing and resource allocation, ensuring that services remain agile and data driven.

 
 



