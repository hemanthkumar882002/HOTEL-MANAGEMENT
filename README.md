# 🏨 Hotel Management Analytics | Power BI

## 📌 Project Overview

This project focuses on analyzing hotel booking and revenue data to understand business performance, customer booking patterns, room utilization, and key operational metrics.

The project was developed using **Microsoft Power BI** to transform raw hotel booking data into interactive dashboards and meaningful business insights.

The analysis helps hotel management monitor performance, identify trends, and support data-driven decision-making.

---

## 🎯 Business Objectives

The main objectives of this project are:

- Analyze hotel booking performance
- Monitor revenue and key business metrics
- Understand booking trends over time
- Analyze room and property performance
- Compare hotel performance across different properties
- Identify customer booking patterns
- Analyze occupancy and room utilization
- Identify areas for improving hotel performance
- Present insights through interactive Power BI dashboards

---

## 🛠️ Tools & Technologies

- **Power BI** – Data visualization and dashboard development
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculated metrics
- **CSV** – Source datasets
- **Data Modeling** – Relationships between fact and dimension tables

---

## 📂 Dataset

The project contains multiple datasets organized into fact and dimension tables.

### Dimension Tables

- `dim_date.csv` – Date-related information such as date, month, week, and day type
- `dim_hotels.csv` – Hotel/property information
- `dim_rooms.csv` – Room category and room-related information

### Fact Tables

- `fact_bookings.csv` – Detailed hotel booking information
- `fact_aggregated_bookings.csv` – Aggregated booking and room-related information

---

## 🧹 Data Preparation

The data was prepared before building the dashboard.

Key steps included:

- Importing CSV datasets into Power BI
- Cleaning and transforming data using Power Query
- Checking data types
- Handling missing and inconsistent values
- Creating relationships between tables
- Building a structured data model
- Creating calculated measures using DAX

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of hotel business performance.

### Key Areas of Analysis

- Hotel performance
- Booking trends
- Revenue analysis
- Room performance
- Occupancy and utilization
- Property-level comparison
- Time-based performance analysis

Interactive filters and slicers allow users to analyze the data from different perspectives.

---

## 📈 Key Insights

The analysis helps identify:

- Trends in hotel bookings over time
- Differences in performance between properties
- Changes in revenue and booking performance
- Room categories with different levels of demand
- Weekday versus weekend booking patterns
- Areas where hotel performance can be improved

---

## 📁 Project Structure

```text
HOTEL-MANAGEMENT/
│
├── DATA SET/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   └── fact_bookings.csv
│
├── HOTEL MANAGEMENT1.pbix
│
└── README.md