# Recruitment Analytics Dashboard

An end-to-end recruitment analytics solution built in Excel to track and optimise the full hiring lifecycle — from sourcing to placement.


# Project Overview

This dashboard was developed to move beyond basic reporting and provide **data-driven insights** into the full recruitment process, including:

- Candidate sourcing (headhunting vs applications)
- Response rates and engagement tracking
- Funnel conversion analysis
- Weekly performance trends
- KPI monitoring with visual indicators

The solution allows recruiters and management to **instantly assess performance** without relying on manual weekly updates.

#  Key Features

- 📊 Dynamic dashboard with slicers (weekly filtering)
- 📉 Cumulative recruitment funnel:
  - Headhunted → Contacted → Interested → Submitted → Interviewed → Placed
- 🎯 KPI indicators using conditional formatting:
  - 🔴 Red → Action required
  - 🟡 Yellow → Moderate performance
  - 🟢 Green → Target achieved
- 📅 Weekly trend analysis
- ⚡ Fully dynamic calculations that update automatically based on selected time period


#  Technical Implementation

This project incorporates multiple Excel techniques to simulate a real-world analytics system:

-  **GETPIVOTDATA** for dynamic KPI extraction from pivot tables
-  **SUM formulas** used to construct a **cumulative funnel** (not a standard funnel)
-  **Backend Pivot Tables** used as the data engine (hidden and protected)
-  **Data Validation** to enforce consistent status tracking
-  **Conditional Formatting** for performance monitoring
-  **Workbook & Sheet Protection** to safeguard logic and formulas
-  **Dynamic calculations** driven by slicers and pivot interactions


#  Data Preparation

-  **Power Query** used to clean and structure job specification data
-  Data is **refreshable**, allowing seamless updates without rebuilding the model
-  Standardisation of raw and inconsistent input data


# Funnel Logic (Key Highlight)

This dashboard uses a **cumulative funnel approach**:

- Candidates are counted based on their **latest status**
- Each stage reflects progression, not duplication
- Prevents inflated numbers seen in traditional funnel reporting

This provides a **true and accurate view of pipeline conversion**.


# Problem Solving

This solution was designed to address real operational challenges:

-  Lack of visibility into headhunting effectiveness
-  High "No Response" rates with no structured tracking
-  Manual weekly reporting and inconsistent feedback
-  No end-to-end view of the recruitment lifecycle

The dashboard enables:
- Instant performance analysis
- Clear identification of bottlenecks
- Data-driven decision making
- Reduced reliance on manual reporting


## 📂 Project Structure

- `/v1` → Initial headhunting report (basic tracking)
- `/v2` → Full analytics dashboard with KPIs and funnel analysis
- `/screenshots` → Dashboard previews and supporting visuals


## 📸 Dashboard Preview

![Dashboard](screenshots/Full%20Dynamic%20Recruitment%20Dashboard%20-%20Good%20week.jpeg)


## 🛠 Tools Used

- Microsoft Excel
- Pivot Tables
- Power Query
- GETPIVOTDATA
- Conditional Formatting
- Data Validation


#  Outcome

This solution transforms recruitment tracking into a **fully automated, insight-driven process**, enabling:

- Real-time performance monitoring
- Improved sourcing strategy
- Better decision-making across the recruitment pipeline
