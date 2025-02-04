# Road Accident Analysis Excel Project

## Project Overview

**Project Title**: Road Accident Analysis  

The main objective of the project is to analyse a dataset containing information about road accidents.The project involved downloading the dataset, performing exploratory data analysis (EDA), and answering specific questions using excel.

## Objectives

1. **Download the required dataset**:
2. **Data Cleaning**: Identify and remove any records with missing or null values.
3. **Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.
4. **Analysis**: Use Excel to answer specific questions and derive insights from the provided data.

## Project Structure

### 1. Dataset Download

- The first step was to download the dataset 

### 2. Data Exploration & Cleaning

- **Count number of records**: Determine the total number of records in the dataset.
- **Column Count**: Identify all the columns in the dataset
- **Null Value Check**: Check for null values in the dataset and delete records with missing data.
- **Duplicate Check**: Check for duplicates in the primary column 'Accident index'
- **Spelling Checks**: A filter was applied and each column was checked to ensure no spelling errors existed. One error found was the presense of the words 'fatal' and 'fetal' in the Accident_Severity Column and corrections to the correct spelling were made in this and other columns in the dataset.

### Data Processing
One of the requirents on the KPI's is to show the monthly trend of each year, thus, two new columns named 'Month' and 'Year' were created and, using the TEXT() function, months and years were extracted from the Accident Column.

### 3. Data Analysis & Visualisation

- **PROJECT REQUIREMENTS**
The client requires a dashboard showing Road Accidents in the year 2021 and 2021 so that they can gain insight on the below requirements:
-**Primary KPI**: Total Casualties that took place
-**Primary KPI's**: Total Casualties and percentage of total casualties with respect to the accident severity and the maximum casualties based on type of vehicle
-**Secondary KPI's**: Total casualties with respect to vehicle type
-Monthly trend showing a comparison of casualties for the Current and Previous year
-Maximum casualties by road type
-Distribution of total casualties by Road Surface
-Relationship between Casualties by Area/ Location  and by Day/Night

**DASHBOARD CREATION**
A new worksheet named 'Dashboard' was created, placeholders were created and then all the charts that were created in the previous steps were inserted in the placeholder to create the full dashboard.

The following steps were done to create worksheets and pivot tables
- **KPI's Worksheet:**  
  - Pivot tables show total casualties and casualties by accident severity, visualized with donut charts. 
  - Slicers filter data by accident timeline and urban/rural location.

- **Vehicle Type Analysis:**  
  - Pivot table displays casualties by vehicle type; calculated items consolidate similar types, visualized with icons.

- **Monthly Trend Worksheet:**  
  - Pivot tables for monthly casualties (2021–2022) with a line chart showing trends.

- **Road Type Worksheet:**  
  - Pivot table for casualties by road type, visualized with a bar chart.

- **Tree Map Worksheet:**  
  - Pivot table for casualties by road surface; calculated items consolidate similar surfaces, visualized with a tree map.

- **Donut Chart Worksheet:**  
  - Two pivot tables: one for urban/rural casualties, another for Daylight/Night casualties; calculated items consolidate time categories, both visualized with donut charts.
---
DASHBOARD
![Road Accident Dashboard](https://github.com/Gavercio97/Road-Accident-Excel-Project/blob/main/assets/images/RTA%20Dashboard.png)
---
## Findings

- **Severity of Accidents**: The analysis showed that most accidents were slightly severe, accounting for 84.1% of the total. Serious Casualties came second with 14.2% and Fatal Casualties accounted for 1.7%
- **Casualties by Vehicle Type**: Cars were the most common type of vehicle involved in the casualties, followed by bikes and vans respectively.
- **Casualties by Road Type**: Single carriageway accounted for the highest casualties, followed by dual carriageway and then Roundabouts.
- **Casualties by Location/ Area**: Most casualties occur in urban areas compared to rural areas.
- **Casualties by Light Conditions**: Most casualties occur in Daylight compared to Dark hours.
- **Casualties by Road Surface**: Dry surfaces accounted for the largest casualties, followed by wet and snow/ice surfeaces respectively.


## Summary
This project presents the results of an analysis of road accidents using various segments. The analysis focuses on segments like vehicle type, severity of the casualties, casualties by road surface, casualties by location, light conditions etc. The insights gained from this analysis will help come up with campaigns to sensitize the public about the type of conditions that make up the majority of road accidents and what can be done to help minimize the risks associated with each factor.
