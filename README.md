# Morocco Electricity Consumption Analysis

## Project Overview

This project explores electricity consumption patterns across three geographical zones in Morocco using Python. The analysis focuses on understanding consumption trends, comparing the three zones, examining hourly, daily and monthly patterns, and investigating relationships between electricity consumption and environmental factors.

## Business Problem

An energy management organisation wants to understand electricity demand across three geographical zones to support better energy planning, demand forecasting and resource allocation.
This project uses data analysis and visualisation to identify consumption patterns and provide actionable recommendations.

## Dataset Description

The dataset contains electricity consumption readings and environmental measurements, including:

- Datetime
- Temperature
- Humidity
- WindSpeed
- GeneralDiffuseFlows
- DiffuseFlows
- PowerConsumption_Zone1
- PowerConsumption_Zone2
- PowerConsumption_Zone3
The available dataset contains 21,539 records, covering January 1 to May 30, 2017.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Data Understanding and Exploration

Inspected the dataset structure, data types, summary statistics, missing values, duplicate records and date range.

2. Data Cleaning and Preparation

Checked for missing values and duplicate timestamps, investigated potential outliers and created time-based features such as year, month, day, hour and day of the week.

3. Electricity Consumption Analysis

Compared average consumption across the three zones and examined hourly, weekly and monthly consumption patterns.

4. Environmental Relationship Analysis

Investigated the relationships between electricity consumption and temperature, humidity and wind speed using correlation analysis.

5. Data Visualisation

Created charts using Matplotlib, Seaborn and Plotly to communicate the findings.

6. Business Insights and Recommendations

Identified important consumption patterns and developed recommendations to support energy management and planning.

## Key Findings

- Zone 1 recorded the highest average electricity consumption.
- All three zones recorded their highest average consumption at approximately 8 PM.
- Zone 1 and Zone 2 recorded their highest monthly averages in May, while Zone 3 peaked in April.
- Temperature showed a weak positive relationship with electricity consumption.
- Humidity showed a weak negative relationship with electricity consumption.
- Wind speed had a very weak relationship with consumption across the three zones.

## Business Recommendations

1. Prioritise monitoring and planning for evening peak demand.
2. Develop zone-specific energy management strategies.
3. Investigate unusually high readings in Zone 3.
4. Improve demand forecasting by combining historical consumption with additional relevant variables.
5. Schedule suitable maintenance activities during lower-demand periods.

## Project Files

- "Week_5_Morocco_Electricity_Analysis.ipynb" – Jupyter Notebook containing the analysis.
- "Morocco_Electricity_Cleaned" – Cleaned dataset.
- "Morocco_Electricity_Charts.zip" – Project charts and visualisations.
- "Morocco_Electricity_Analysis_Report.pdf" – Analytical report.

## Limitations

The available dataset covers January 1 to May 30, 2017, rather than the full year described in the original project brief. Therefore, the findings may not represent seasonal patterns throughout the entire year.

Correlation results indicate association, not causation.

## Conclusion

This project demonstrates how Python can be used to explore electricity consumption patterns, identify trends, investigate relationships and communicate findings that can support data-driven energy management decisions.

