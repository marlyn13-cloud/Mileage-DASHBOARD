# Healthcare Operations & Route Optimization Analysis

## Project Overview
This project analyzes two years of front-line nursing timesheets to evaluate travel efficiency, patient volume, and workload distribution. The goal of the analysis is to identify scheduling bottlenecks and recommend data-driven routing improvements to reduce travel time and operational costs.

## Tools & Technologies Used

Data Cleaning: Used Excel Power Query to extract data from 100+ separate reporting sheets into a CSV.

SQL: Used to query, filter, and aggregate KPI metrics (Sum of Miles, Average Miles).

Power BI: Used to build an interactive dashboard highlighting travel trends.

## The Challenge (Data Engineering)
Before any analysis could begin, I designed a cleaning process to strip the visual formatting and handle null values.

## Key Business Insights

High Volume vs. Low Efficiency: While Paterson accounted for the highest total volume of care (70 total miles driven), it was highly efficient due to patient density.

Average: Towns like Woodland Park (6.0 avg. miles) and Hawthorne (5.6 avg. miles) represented the highest travel cost per visit.

Actionable Recommendation: By restructuring the schedule to group all Woodland Park and Hawthorne visits onto dedicated, consecutive days, the healthcare provider can significantly reduce per-visit travel costs and free up nursing hours for additional patient care.

SQL QUERIES USED TO CLEAN DATA:

total miles:

<img width="1007" height="782" alt="image" src="https://github.com/user-attachments/assets/1e307170-ea6e-4fd7-942b-87fc11708e3d" />

average miles:

<img width="1104" height="815" alt="image" src="https://github.com/user-attachments/assets/9766d9dd-9baf-4fd7-ad1e-1b6444ba7145" />

DASHBOARD USING POWER BI

<img width="618" height="503" alt="image" src="https://github.com/user-attachments/assets/195d5d4d-3e09-4713-9cca-1ff83b528dcd" />
