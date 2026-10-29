
# Emergency Department Analytics | Power BI

**Healthcare Business Intelligence · Data Analytics · Power BI · DAX · ETL**

## Project Overview

This project develops a Business Intelligence solution for a **simulated Emergency Department (ED) dataset inspired by the operational context of Hôpital Charles Nicolle, Tunisia**.

Emergency departments face operational challenges such as overcrowding, prolonged waiting times, inefficient resource allocation, and patients leaving before receiving medical attention. This project explores these challenges through data analysis and interactive Power BI dashboards.

The objective is to transform simulated operational data into actionable insights, monitor key performance indicators (KPIs), identify potential bottlenecks, and support data-driven decision-making.

### Data Disclaimer

**The dataset used in this project is simulated and does not represent actual hospital records or verified operational performance at Hôpital Charles Nicolle.** The hospital provides the contextual setting for the business problem; all analyses and findings are based on simulated data.

## Business Problem

The project explores several important healthcare management challenges:

- **Emergency department overcrowding:** Understanding variations in patient arrivals and workload.
- **Waiting times:** Monitoring the time patients wait before receiving medical attention.
- **Patients Leaving Without Being Seen (LWBS):** Measuring the proportion of patients who leave before being seen by a healthcare professional.
- **Length of stay:** Analyzing the time patients spend in the emergency department.
- **Bed occupancy and resource utilization:** Exploring operational pressure and available capacity.
- **Estimated revenue:** Examining the potential financial contribution of emergency department activity.

## Project Objectives

- Prepare and clean simulated emergency department data for analysis.
- Design a dimensional data model suitable for Business Intelligence reporting.
- Develop DAX measures to calculate operational and financial KPIs.
- Build interactive Power BI dashboards to monitor performance.
- Analyze temporal patterns and identify potential operational bottlenecks.
- Translate analytical findings into practical, data-driven recommendations.

## Technical Stack

| Technology | Purpose |
|---|---|
| Python | Data preparation and transformation |
| Jupyter Notebook | ETL workflow development |
| Pandas | Data cleaning and manipulation |
| Power BI | Interactive dashboards and visualization |
| DAX | KPI calculations and analytical measures |
| Star Schema | Dimensional data modeling |
| CSV | Storage and exchange of cleaned data |

## Data Preparation and ETL

The project incorporates an Extract, Transform, Load (ETL) workflow to prepare the simulated dataset for analysis.

The workflow includes:

1. **Extraction:** Loading the source dataset into the data preparation environment.
2. **Transformation:** Cleaning and organizing the data, addressing data-quality issues, and preparing analytical fields.
3. **Loading:** Exporting the cleaned dataset for use in Power BI.
4. **Documentation:** Preparing a data dictionary to describe the dataset's fields and meanings.

The objective is to establish a consistent analytical foundation before building dashboards and calculating KPIs.

## Data Modeling

A star-schema approach is used to organize the data into a structure suitable for Business Intelligence reporting.

Dimensional modeling supports data aggregation, filtering, and comparisons across relevant analytical dimensions, helping make the Power BI model easier to navigate and maintain.

## Key Performance Indicators (KPIs)

The analytical model focuses on the following indicators:

| KPI | Purpose |
|---|---|
| Total ED Visits | Measures the volume of emergency department activity |
| Average Door-to-Doctor Time | Evaluates how long patients wait before seeing a doctor |
| LWBS Rate | Measures the proportion of patients who leave without being seen |
| Average Length of Stay | Helps assess patient flow and time spent in the department |
| Bed Occupancy Rate | Monitors pressure on available capacity |
| Total Estimated Revenue | Estimates the financial contribution of emergency department activity |

DAX measures support KPI calculations and interactive reporting. Time-based comparisons, including month-over-month (MoM) and year-over-year (YoY) analysis, are also part of the analytical approach.

*All KPI values and resulting findings are based on simulated data and should not be interpreted as actual hospital performance.*

## Dashboard Design

The Power BI solution is organized around complementary analytical perspectives.

### 1. Executive Summary

Provides a high-level overview of emergency department performance through key indicators, trends, and comparisons. It is designed to help decision-makers quickly identify areas that may require attention.

### 2. Operational Deep Dive

Supports detailed exploration of emergency department activity, waiting times, length of stay, patient flow, and operational pressure.

### 3. Interactive Analysis

Slicers, drill-through functionality, and additional visualizations allow users to investigate performance across available dimensions instead of relying solely on static reports.

### 4. Trend Analysis and Forecasting

Time-based analysis explores changes in simulated emergency department activity and provides a basis for discussing potential forecasting applications in operational planning.

## Expected Business Value

The solution demonstrates how Business Intelligence can help healthcare stakeholders:

- Identify periods of elevated emergency department activity.
- Monitor waiting times and patient-flow indicators.
- Explore potential operational bottlenecks.
- Track patients leaving without being seen.
- Understand simulated bed utilization and resource pressure.
- Examine trends in estimated revenue.
- Support evidence-based discussions about staffing, capacity planning, and process improvement.

These applications demonstrate the analytical potential of BI dashboards. They do not establish real-world improvements in hospital performance.

## Skills Demonstrated

- Data cleaning and transformation
- ETL workflow development
- Dimensional data modeling
- Power BI dashboard development
- DAX measures and KPI design
- Time-based and trend analysis
- Healthcare operational analytics
- Data visualization and storytelling
- Business problem-solving and decision support

## Repository Structure

The repository can be organized as follows:

```text
ED-Business-Intelligence/
├── data/
│   └── cleaned_dataset.csv
├── ETL_process.py
├── powerbi/
│   └── emergency_department_dashboard.pbix
└── README.md
```


## Conclusion

This project demonstrates how Business Intelligence tools can transform simulated healthcare data into meaningful operational insights.

By combining data preparation, dimensional modeling, DAX calculations, and interactive visualization, the solution provides a framework for monitoring emergency department KPIs, exploring operational patterns, and identifying potential opportunities to improve patient flow and resource utilization.

**The broader goal is to bridge the gap between raw data and actionable insights that support better operational decision-making.**

---

**Disclaimer:** This is an educational and analytical project based on simulated data. It is not an official Hôpital Charles Nicolle system, and its results do not represent verified clinical, operational, or financial outcomes.
