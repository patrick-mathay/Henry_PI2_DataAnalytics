## Introduction
This project simulates the role of a Data Analyst who is part of the data analysis team of a consulting company to which the Road Mobility and Safety Observatory (OMSV) requested the development of a data analysis project.

The purpose of this project is to generate information that allows local authorities to take measures to reduce the number of fatal victims from road accidents in the Autonomous City of Buenos Aires (CABA). 
For this, a dataset on homicides in road accidents that occurred in the City of Buenos Aires during the period 2016-2021 is made available.

## Data
For this project, the Fatal Victims in Road Accidents Database in Excel format was used, containing two data tabs:
- INCIDENTS: which contains a row of incidents with a unique ID and the associated temporal, spatial, and participant variables.
- VICTIMS: contains one row for each victim of the incidents and the variables age, sex, and mode of transport associated with each victim. It is linked to INCIDENTS by the incident ID.

## Technologies Used
For the development of this project, Python and Pandas were used for data extraction, transformation, and loading processes, as well as for exploratory data analysis.
Finally, Power BI was used for the construction of an interactive dashboard.

## ETL and EDA
First, a process of extraction, transformation, and loading of the data (ETL) was carried out for both "INCIDENTS" and "VICTIMS", where variable names were standardized, nulls and duplicates were analyzed, redundant or heavily missing value columns were removed, among other tasks. 
Once this process was completed for the two datasets of "Homicides", the two sets were joined into a single one called df_homicides.

Second, an exhaustive exploratory data analysis (EDA) was conducted to identify patterns that allow generating information to enable local authorities to take measures to reduce the number of fatal victims of road accidents.

## Analysis of the Data
Time distribution, victim profiles, roles, and means of transportation were analyzed in concert with the geographical distrobution of accidents. Relevant patterns were identified that can inform decision-making.

## KPIs (Key Performance Indicators)
Based on the analysis conducted, two objectives and associated KPIs were proposed:

Reduction of the Homicide Rate in Road Accidents
The goal is to reduce the homicide rate in road accidents by 10% over the last six months compared to the previous semester.

Reduction of Fatal Motorcycle Accidents
A 7% reduction in the number of fatal motorcycle accidents in the last year compared to the previous year is proposed.

## Libraries Used
- pandas
- numpy
- seaborn
