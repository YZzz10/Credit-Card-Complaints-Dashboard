# Credit Card Complaints Dashboard

## Project Objective


## Dataset Used
<a href="https://github.com/YZzz10/Credit-Card-Complaint-Dashboard/blob/main/Credit%20Card%20Data.xlsx">Credit Card Complaint Dataset</a>

## KPI Metrics
- Total number of complaint records.
- Number of complaints within the last 12 months based on the most recent available date in the dataset.
- Number of complaints marked as timely responses.
- Percentage of complaints marked as timely responses relative to total records.
- Number of complaints marked as "In Progress".
- Percentage of complaints marked as "In Progress" relative to total records.

## Visualization Overview
- The Trend Chart shows complaint trends over time, with a parameter-driven filter that dynamically adjusts the time granularity between day, week, month, quarter, and year.
- 

## View Dashboard
<a href="">View Dashboard</a> (Please use “See this in Full Screen” if the dashboard elements overlap.)

## Process
- The “Date Received” field was incorrectly interpreted by Tableau as a year-first format. This issue was resolved by converting the field to string and re-parsing it using DATEPARSE("dd-MMM-yy", [Date Received]) to ensure accurate time-series analysis.
- Missing values were handled within the dashboard by excluding null entries to ensure clarity and accuracy in the charts.

## Dashboard
<img width="1600" height="900" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/c245314d-fdc7-45a3-8249-0824aa3fec47" />


## Project Insight
-
-
-

## Final Conclusion
-
-
-
