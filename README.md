# Credit Card Complaints Dashboard

## Project Objective
The objective is to analyze complaint patterns over time, channels, and categories to support data-driven workforce planning and improve overall service efficiency.

## Dataset Used
- <a href="https://github.com/YZzz10/Credit-Card-Complaint-Dashboard/blob/main/Credit%20Card%20Data.xlsx">Credit Card Complaint Dataset</a>

## KPI Metrics
- Total number of complaint records.
- Number of complaints within the last 12 months based on the most recent available date in the dataset.
- Number of complaints marked as timely responses.
- Percentage of complaints marked as timely responses relative to total records.
- Number of complaints marked as "In Progress".
- Percentage of complaints marked as "In Progress" relative to total records.

## Visualization Overview
- **Trend** shows complaint trends over time, with a parameter-driven filter that dynamically adjusts the time granularity between day, week, month, quarter, and year.
- **State-wise Complaints** map shows the geographic distribution of complaints across the United States, with the ability to switch between filled and density map views via the "Select Map" filter.
- **Top Issues** displays the top 10 complaint issues by total complaint volume.
- **Company Response** displays the distribution of response status by count and percentage of total responses.
- **Daily Complaints** calendar heatmap displays complaint volumes for each day of the month and can be updated using the "Date Received" filter to select different month–year combinations.
- **Submitted Via** displays the percentage of complaints submitted through different channels.

## View Dashboard
<a href="https://public.tableau.com/app/profile/yixin.zhu3122/viz/Book1_17788051728160/CreditCardComplaintsDashboard">View Dashboard</a> (Please use “See this in Full Screen” if the dashboard elements overlap.)

## Process
- Transformed binary categorical values into numeric encoding to facilitate quantitative analysis.
- Missing values were handled within the dashboard by excluding null entries to ensure clarity and accuracy in the charts.

## Dashboard
<img width="1600" height="900" alt="Screenshot 2026-05-29 at 5 11 17 PM" src="https://github.com/user-attachments/assets/5483e4b6-2069-4f6c-bf74-66ec3226ed0f" />

## Project Insight
- When analyzing complaints by day of the week, Thursday and Friday consistently show lower complaint volumes, with this lower-volume pattern observed across most time periods, while the remaining days maintain relatively higher complaint levels.
- There was a noticeable spike in complaint volume around September 2020, during which timely response rates declined slightly, (indicating that existing capacity may be approaching its upper limit and could require additional staffing during sustained high-demand periods).
- Web remained the dominant submission channel over time. Notably, fluctuations in total complaint volume closely mirrored trends in Web-submitted complaints, indicating that overall volume changes were primarily driven by the Web channel, while other channels remained relatively stable and contributed minimally throughout the period. This suggests that workforce capacity should be prioritized for the Web support channel, rather than reallocating significant resources to other channels such as phone or email support.
- Among complaint issue categories, Disputes have consistently remained the most common issue type throughout the analyzed period.
Finally, further investigation into the underlying drivers of dispute-related complaints could help reduce recurrence and lower the overall proportion of this category over time, further investigation into the underlying drivers of dispute-related complaints could help reduce recurrence and lower the overall proportion of this category over time.

## Final Conclusion
- This suggests that staff scheduling could be optimized by reallocating resources away from lower-volume days toward peak days to improve overall operational efficiency.
- This indicates that sustained periods of above-normal complaint volume may require additional staffing capacity to maintain service levels and protect response times.
-
