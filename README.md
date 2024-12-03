# Hospitality Analytics Dashboard - Excel
Welcome to the AtliQ Grand Hospitality Dashboard project! This project was created to provide insightful data analysis for AtliQ Grand, a luxury hotel chain facing revenue challenges in India's competitive hospitality market. Using Excel and a comprehensive dataset, the dashboard provides crucial insights for strategic decision-making.

# Project Overview
This Excel-based project analyzes the performance of AtliQ Grand, a renowned luxury hotel chain, aiming to address revenue challenges and market share declines caused by increasing competition and ineffective management decisions. By utilizing interactive features like PivotTables and charts, this project provides actionable insights to optimize operations and increase revenue in the luxury and business hotel segments.

Key Metrics Analyzed:

Revenue trends,Occupancy rate (%),Average ratings,Utilized capacity,Cancellation rates

These metrics are visualized using Calculated Measures and custom formulas. The analysis includes tracking weekly performance trends, examining room utilization, and evaluating customer satisfaction to support data-driven decision-making.This project demonstrates a comprehensive data analysis process—from importing and validating data to creating Calculated Measures for tailored insights. It showcases proficiency in Excel functions (including VLOOKUP, IF statements, and data validation) and data visualization techniques (like PivotTables, charts, and conditional formatting) within the hospitality industry.

# Data Model
![image alt](https://github.com/Saktalmale16/Excel_dashboard_project-3/blob/6bcfdc1e90fa676f493f8c6c236f9ecec7c4c8fb/Data%20Model.PNG)

# Project Screenshot

![image alt](https://github.com/Saktalmale16/Excel_dashboard_project-3/blob/613240ec11ab3fec58ed614aafe002647a66b48d/Excel%20Dashboard.PNG)

# Calculated Measure

Average Rating = Average(fact_bookings_2[ratings_given])

Total Revenue = [Sum of revenue_realized]

Utilize capacity = SUM(fact_aggregated_bookings[capacity])

Occupancy % = [total bookings]/[Sum of capacity]

Cancellation rate = [cancellation amount]/[Sum of revenue_generated]




# Key Performance Indicator

Total Revenue: 1,709M

Average Rating: 3.62

Occupancy Rate: 57.87%

Cancellation Rate: 14.88%

Utilized Capacity: 232

# Informative Charts

Weekly Treand

Weekly Report

Revenue By Booking Status

Revenue and Booking By Daytype

Revenue By Room Class

Revenue By Cities
