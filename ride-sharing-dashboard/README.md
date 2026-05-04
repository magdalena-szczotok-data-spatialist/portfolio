# Ride Analytics Dashboard – Power BI Portfolio Project

## Project Overview

This project presents an interactive Power BI dashboard built using publicly available NYC Yellow Taxi trip data.  
The goal of the project is to analyze ride demand, revenue trends, trip duration patterns, and user behavior in order to generate actionable operational insights.

The dashboard was designed as a portfolio project for Data Analyst roles focused on analytics, dashboards, operational reporting, and business recommendations.

---

## Dashboard Pages

### 1. Landing Page

A simple navigation page introducing the dashboard and allowing users to move between report sections.

### 2. Operational Overview

High-level view of key performance metrics, trends, and overall ride activity.

This page includes:
- Total rides
- Total revenue
- Average trip duration
- Average fare
- Ride volume over time
- Revenue trend over time
- Top pickup locations
- Ride duration distribution
- Date and passenger count filters

### 3. Ride Behavior Analysis

Detailed analysis of ride patterns, user behavior, and operational drivers influencing demand and performance.

This page includes:
- Ride volume by hour of day
- Average ride duration by hour
- Ride duration vs revenue analysis
- Passenger count analysis
- Month and date-based filtering

---

## Tools Used

- Power BI
- Power Query
- DAX
- Data modeling
- Public NYC Taxi trip data

---

## Dataset

Data source: NYC Taxi & Limousine Commission Trip Record Data  
Dataset used: Yellow Taxi Trip Records for February and March 2023  

Source:  
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Raw data files are not included in this repository due to file size.

---

## Key Metrics

The dashboard focuses on the following key metrics:

- **Total Rides** – total number of completed rides
- **Total Revenue** – total amount generated from rides
- **Average Trip Duration** – average ride duration in minutes
- **Average Fare** – average base fare excluding tips, tolls, and other charges
- **Ride Volume by Day** – daily demand trend
- **Revenue by Day** – daily revenue performance
- **Ride Duration Distribution** – distribution of trips by duration ranges
- **Top Pickup Locations** – highest-demand pickup zones

---

## Key Insights

- Ride demand peaks during evening hours and shows noticeable increases during weekends.
- Most trips are short, typically between 5 and 15 minutes, indicating high-frequency urban usage.
- Revenue closely follows ride volume trends, suggesting that demand is the primary driver of earnings.
- Ride activity is concentrated in selected high-demand pickup locations.
- Longer trips generate higher revenue per ride but occur less frequently.

---

## Data Preparation

The data was cleaned and transformed before dashboard development.

Main preparation steps:
- Combined two monthly datasets into one table
- Created a clean date column from pickup datetime
- Calculated ride duration in minutes
- Removed unrealistic trips shorter than 2 minutes or longer than 120 minutes
- Removed records with non-positive monetary values
- Created a calendar table for date-based filtering
- Built DAX measures for KPIs and trend analysis

More details are available in `docs/data_cleaning_notes.md`.

---

## Screenshots

### Landing Page

![Landing Page](screenshots/01_landing_page.png)

### Operational Overview

![Operational Overview](screenshots/02_operational_overview.png)

### Ride Behavior Analysis

![Ride Behavior Analysis](screenshots/03_ride_behavior_analysis.png)

---

## Business Value

This dashboard demonstrates how raw operational ride data can be transformed into clear, decision-ready insights.  
It supports analysis of demand patterns, revenue performance, user behavior, and operational hotspots.

The project shows practical skills in:
- data cleaning
- dashboard design
- business analysis
- KPI development
- DAX measures
- data storytelling
- operational insight generation

---

## Recommendations

Based on the analysis, operational teams could:

- Monitor evening and weekend demand more closely
- Allocate resources to high-demand pickup zones
- Track revenue changes alongside ride volume
- Use ride duration patterns to better understand customer behavior
- Investigate locations or time periods with unusual demand fluctuations

---

## Author

Magdalena Szczotok  
Data Analyst / Geospatial Data Specialist
