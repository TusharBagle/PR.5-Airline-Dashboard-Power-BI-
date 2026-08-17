# PR.5 Airline Dashboard (Power BI)

✈️ Airline Performance & Flight Cancellation Analysis — Power BI

<p align="center">
  <img src="Images/Airline%20Overview.png" alt="Airline Dashboard Overview" width="950"/>
</p>

<p align="center">
  <b>Interactive Power BI Dashboard | Flight Operations • Cancellation Trends • Delay Analysis • Route & Airport Performance • Forecasting</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/SQL-Data%20Analysis-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Years-2019--2023-00A8A8?style=for-the-badge"/>
</p>

📌 Project Overview

The Airline Performance & Flight Cancellation Analysis dashboard is an interactive Power BI solution designed to analyze airline operations across flight volume, cancellations, delays, on-time performance, routes, airports, and yearly/monthly trends.

The dashboard transforms large-scale flight operational data into an executive-friendly analytical experience, allowing users to move from high-level KPIs to airline-level performance, geographic analysis, detailed flight records, and trend/forecast analysis.

🎯 Business Objective

The primary objective is to answer questions such as:

How many flights were operated during the analysis period?

What percentage of flights were cancelled?

Which airlines handled the highest flight volumes?

Which airlines experienced the highest cancellation counts?

Which airlines have the highest average departure delays?

What are the major reasons for flight cancellations?

How does on-time performance change by year?

Which airports handle the highest flight volumes?

Which states have higher cancellation rates?

How do monthly flight volumes and delays change over time?

What operational patterns should airline management monitor?

📊 Dashboard Highlights

KPI

Dashboard Result

Total Flights

3M

Total Cancelled Flights

79K

Cancellation Rate

2.64%

Average Departure Delay

10.10 min

Average Arrival Delay

4.26 min

Overall On-Time Rate

82.32%

Analysis Period

2019–2023

Note: KPI values shown above reflect the dashboard screenshots and may change when filters are applied.

🗂️ Dashboard Pages

1. ✈️ Airline Overview

<p align="center">
  <img src="Images/Airline%20Overview.png" alt="Airline Overview Dashboard" width="950"/>
</p>

📌 Purpose

The Airline Overview page provides the executive-level summary of flight operations, cancellations, cancellation reasons, and on-time performance.

📈 Key Visuals

Total Flights

Total Cancelled Flights

Cancellation Rate

Cancelled Flights by Month

Cancellation Reason Distribution

Detailed Flight Cancellation Table

On-Time Rate by Flight Year

Airline and flight-level filtering

💡 Business Insights

The dashboard contains approximately 3M flights, while around 79K flights were cancelled.

The overall cancellation rate is approximately 2.64%, indicating that cancellations represent a relatively small share of total flight operations.

Weather-related cancellations are the largest cancellation category, making weather monitoring an important operational consideration.

Monthly cancellation volumes fluctuate considerably, indicating that cancellation risk is not evenly distributed throughout the year.

On-time performance varies by year, showing that operational reliability changes over time.

The highest cancellation months should be investigated alongside weather conditions, airport congestion, and airline operating patterns.

🎯 Business Value

This page is designed for executive monitoring, allowing management to quickly identify whether cancellation and punctuality KPIs require further investigation.

2. 📊 Airline Performance & Cancellation Analysis

<p align="center">
  <img src="Images/Airline%20Performance.png" alt="Airline Performance Dashboard" width="950"/>
</p>

📌 Purpose

The Airline Performance page compares airlines using operational KPIs and highlights differences in flight volume, cancellations, and on-time performance.

📈 Key Visuals

Total Flights

Total Cancelled Flights

Cancellation Rate

On-Time Rate

Flight Cancellations by Cause

Flight Outcome Distribution

Airline Comparison

Airline Performance Overview

Overall On-Time Rate vs Target

💡 Business Insights

Southwest Airlines has the highest flight volume in the dashboard, followed by Delta Air Lines and American Airlines.

High flight volume does not necessarily mean high cancellation performance; airlines should be compared using both absolute cancellations and cancellation rate.

The airline comparison highlights substantial differences in operational scale.

The overall on-time rate is approximately 82.32%, providing a useful benchmark for operational reliability.

Cancellation causes are concentrated in a few major categories, with Weather representing the largest share.

Airlines with lower on-time performance should be investigated further using the delay and cancellation analysis pages.

Comparing airline performance against the overall on-time target helps identify carriers that may require operational improvement.

🎯 Business Value

This page supports airline benchmarking, helping management identify high-volume carriers, cancellation risks, and differences in punctuality.

3. 🌎 Airline Route & Airport Analysis

<p align="center">
  <img src="Images/Airline%20Route%20%26%20Airport%20Map.png" alt="Airline Route and Airport Analysis Dashboard" width="950"/>
</p>

📌 Purpose

The Route & Airport Analysis page provides geographic insight into flight activity, airport volume, and cancellation performance.

📈 Key Visuals

Total Flights by Airline

US Departure Airports — Flight Volume & Average Delay

US State Cancellation Rate Map

Airline-level operational KPIs

Geographic filtering and exploration

💡 Business Insights

Southwest Airlines represents the largest flight volume among the airlines shown.

The airport map identifies major departure locations and allows analysts to investigate where flight activity is concentrated.

Airport-level analysis can reveal locations with both high traffic and elevated average delays.

The state cancellation-rate map highlights geographic differences in cancellation performance.

High-volume airports should receive special attention because even a small percentage increase in delays or cancellations can affect a large number of passengers.

Geographic patterns can help operations teams prioritize airport-level capacity planning and disruption management.

🎯 Business Value

This page helps identify high-volume airports, geographic cancellation hotspots, and operationally important locations.

4. 🔍 Airline Drill-Through Detail

<p align="center">
  <img src="Images/Airline%20Drill%20Through%20Detail.png" alt="Airline Drill Through Detail Dashboard" width="950"/>
</p>

📌 Purpose

The Drill-Through Detail page provides a focused operational view after selecting an airline, flight, route, or other relevant context from the main dashboard.

📈 Key Visuals

Selected-airline operational KPIs

Cancellation analysis

Monthly cancellation trends

Detailed flight-level records

Cancellation reasons

On-time performance

Delay-related information

💡 Business Insights

Drill-through analysis allows users to move from an overall KPI to the underlying operational records.

Users can investigate individual delayed or cancelled flights instead of relying only on aggregated metrics.

Flight-level details help identify whether poor performance is isolated to specific routes, dates, airports, or cancellation causes.

This page is particularly useful for root-cause analysis after an airline or route has been identified as a performance concern.

Detailed records provide supporting evidence for management decisions made from the summary pages.

🎯 Business Value

The drill-through page turns the dashboard from a reporting tool into an investigative analytics solution.

5. 📈 Airline Trends & Forecast

<p align="center">
  <img src="Images/Airline%20Trends%20%26%20Forcast.png" alt="Airline Trends and Forecast Dashboard" width="950"/>
</p>

📌 Purpose

The Airline Trends & Forecast page analyzes monthly and yearly patterns in flight volume and departure delays, while extending historical patterns into future periods.

📈 Key Visuals

Monthly Average Departure Delay

Total Monthly Flight Volume

Monthly Flight Volume by Year

Year-over-year trend comparison

Historical flight-volume patterns

Forecast / future trend visualization

💡 Business Insights

Monthly average departure delays fluctuate throughout the year, showing that delay performance is affected by operational and seasonal factors.

Flight volumes also vary significantly by month.

Year-over-year comparison makes it easier to identify changes in demand and operational activity.

Forecasting provides an indication of potential future flight-volume patterns based on historical trends.

Months showing both high flight volume and high average delay should be prioritized for operational planning.

Trend analysis can support staffing, aircraft utilization, airport capacity planning, and disruption preparedness.

🎯 Business Value

This page supports forward-looking operational planning, allowing decision-makers to combine historical performance with expected future demand.

6. 🧾 Airline Tooltip

<p align="center">
  <img src="Images/Airline%20Tooltip.png" alt="Airline Tooltip Dashboard" width="700"/>
</p>

📌 Purpose

The Airline Tooltip provides additional contextual information when users hover over dashboard visuals.

📈 Key Information

Airline-specific performance

Flight volume

Cancellation metrics

Delay indicators

On-time performance

Additional contextual KPI information

💡 Business Insights

Tooltips reduce visual clutter while keeping additional information accessible.

Users can compare airline performance without navigating away from the current page.

Tooltip-level KPIs make charts more informative without adding multiple additional visuals.

This improves dashboard usability and supports faster decision-making.

🎯 Business Value

The tooltip layer improves dashboard interactivity, usability, and analytical depth without overcrowding the main report pages.

🔎 Cross-Page Business Insights

✈️ 1. Flight Volume

The dashboard analyzes approximately 3M flights across the 2019–2023 period.

The largest airline by flight volume is Southwest Airlines, followed by Delta Air Lines and American Airlines.

Business implication:
High-volume airlines should be evaluated not only by operational scale but also by their cancellation rate, delay performance, and on-time rate.

❌ 2. Cancellation Performance

Approximately 79K flights were cancelled, resulting in an overall cancellation rate of 2.64%.

Business implication:
Although the overall cancellation percentage is relatively low, the absolute number of affected flights is significant. Cancellation analysis should therefore focus on the combination of volume, rate, cause, airline, airport, and seasonality.

🌦️ 3. Cancellation Reasons

Weather is the largest cancellation reason shown in the dashboard.

Business implication:
Airlines and airport operators can use weather forecasting and disruption-management strategies to improve preparedness during high-risk periods.

⏱️ 4. On-Time Performance

The overall on-time rate is approximately 82.32%.

Business implication:
An on-time rate around 82% means that punctuality remains an important operational KPI. Airlines should analyze departure delays separately from arrival delays because delays can propagate through the network.

🛫 5. Departure Delay

The overall average departure delay is approximately 10.10 minutes.

The airline-level analysis shows that average departure delays differ substantially between carriers.

Business implication:
Airlines with higher average departure delays should investigate airport turnaround time, aircraft scheduling, boarding processes, congestion, and operational disruptions.

🗺️ 6. Airport & Geographic Performance

The route and airport page shows that flight activity is concentrated around major airports and geographic regions.

Business implication:
High-volume airports should be monitored closely because operational disruptions at these locations can have a disproportionate impact on the wider flight network.

📅 7. Seasonal & Monthly Patterns

Monthly flight volume and average departure delay vary across the year.

Business implication:
Seasonal patterns can support workforce planning, airport capacity management, aircraft scheduling, and disruption preparedness.

🔮 8. Forecasting

The trend page extends historical monthly flight-volume patterns into future periods.

Business implication:
Forecasting can help airline management prepare for expected changes in demand and allocate operational resources more effectively.

🧭 Dashboard Navigation

The report is structured as an analytical journey:

Airline Overview
       ↓
Airline Performance
       ↓
Route & Airport Analysis
       ↓
Drill-Through Detail
       ↓
Trends & Forecast
       ↓
Tooltip-Level Analysis

Users can start with executive KPIs and progressively move toward airline benchmarking, geographic analysis, root-cause investigation, and forecasting.

🎛️ Interactive Features

The dashboard includes:

Airline Code filtering

Delay Status filtering

Flight Year filtering

Airline comparison

Drill-through analysis

Geographic map exploration

Monthly trend analysis

Forecast visualization

Tooltip-based contextual analysis

Cross-page analytical navigation

📊 Core KPIs

The project focuses on the following operational KPIs:

Total Flights

Measures the overall number of flights analyzed.

Total Cancelled Flights

Measures the number of cancelled flights.

Cancellation Rate

Measures cancelled flights as a percentage of total flights.

Average Departure Delay

Measures the average departure delay in minutes.

Average Arrival Delay

Measures the average arrival delay in minutes.

On-Time Rate

Measures the percentage of flights operating on time.

🧠 Key Analytical Questions

This dashboard was designed to answer:

Which airline operates the highest number of flights?

Which airlines have the highest cancellation counts?

Which airlines have the highest cancellation rates?

What are the major reasons for flight cancellations?

Which airlines experience the highest average departure delays?

How does on-time performance change by year?

Which airports handle the largest flight volumes?

Which geographic areas have higher cancellation rates?

Which months experience higher flight cancellations?

How does monthly flight volume change over time?

Are high-volume months also associated with higher delays?

What does the forecast indicate about future flight volume?

🛠️ Tools & Technologies

Technology

Purpose

Power BI

Dashboard development, data modeling, visualization & analytics

DAX

KPI calculations, measures & analytical logic

Power Query

Data cleaning & transformation

SQL

Data querying & analysis

Python

Data analysis and supporting analytics

Microsoft Bing Maps / Map Visuals

Geographic analysis

GitHub

Project documentation & portfolio hosting

📐 Dashboard Design Approach

The dashboard follows a dark, executive-style aviation theme with:

Consistent KPI cards

Clear visual hierarchy

Airline/aviation navigation

Interactive slicers

Geographic maps

Drill-through analysis

Trend and forecast visuals

Consistent typography

High-contrast analytical visuals

The objective is to keep the dashboard professional, interactive, and decision-oriented rather than simply displaying charts.

📁 Suggested Repository Structure

PR.5-Airline-Dashboard-Power-BI/
│
├── README.md
│
├── Images/
│   ├── Airline Overview.png
│   ├── Airline Performance.png
│   ├── Airline Route & Airport Map.png
│   ├── Airline Drill Through Detail.png
│   ├── Airline Trends & Forcast.png
│   └── Airline Tooltip.png
│
├── Dataset/
│   └── ...
│
└── Power BI/
    └── Airline Dashboard.pbix

🚀 How to Explore the Dashboard

Open the Power BI report.

Start from Airline Overview.

Use the filters to select an airline, year, or delay status.

Compare airline performance using the Airline Performance page.

Explore airport and geographic patterns on Route & Airport Analysis.

Use Drill Through to investigate detailed flight records.

Analyze monthly/yearly trends on Trends & Forecast.

Hover over charts to access additional information through Tooltips.

📌 Project Outcomes

This project demonstrates practical skills in:

Business Intelligence

Power BI dashboard development

Data visualization

DAX measure development

Power Query transformation

KPI design

Airline operational analytics

Geographic analysis

Drill-through reporting

Trend analysis

Forecasting

Business storytelling

💼 Business Impact

The dashboard converts operational flight data into actionable information for:

Airline Operations Teams — monitor delays and cancellations

Airport Management — identify high-volume and high-risk locations

Network Planning Teams — understand route and airport activity

Executive Management — monitor overall operational KPIs

Data Analysts — investigate root causes and trends

Planning Teams — use historical trends and forecasts for resource planning

⭐ Final Takeaway

The Airline Performance & Flight Cancellation Analysis dashboard provides an end-to-end analytical view of airline operations — from executive KPIs and airline benchmarking to airport geography, flight-level investigation, and forecasting.

The key operational metrics show approximately 3M flights, 79K cancellations, a 2.64% cancellation rate, a 10.10-minute average departure delay, and an 82.32% overall on-time rate.

The dashboard demonstrates how Power BI can transform complex operational data into a clear, interactive, and business-focused decision-support solution.

👤 Author

Tushar Bagle

<p align="center">
  ⭐ If you find this project useful, consider giving the repository a star!
</p>
