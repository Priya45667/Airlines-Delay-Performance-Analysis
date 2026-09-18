# ✈️ Airlines Performance & Operational Delay Analysis | Power BI, Python

This dashboard was developed as part of my learning journey in Data Analytics to understand operational flight delays, cancellation causes, and airline efficiency using Power BI and Python.

---

## Project Overview

The **Airlines Performance & Operational Delay Analysis Dashboard** is an interactive Business Intelligence project designed to analyze massive aviation operational data from 2003 to 2022. The primary objective of this project is to evaluate flight punctuality, uncover root causes behind flight delays, and identify operational bottlenecks across major US airlines and airport hubs.

Flight delays and cancellations are major challenges in aviation operations because they increase operational costs, disrupt passenger schedules, and severely affect fleet efficiency. This dashboard empowers aviation analysts and operational managers to evaluate carrier performance by breaking down delays into carrier issues, weather impacts, late aircraft cascading effects, and airport-level congestion.

---

## Project Objectives

The main objectives of this project are:
* Analyze flight operations and overall delay patterns across **121 Million flight records**.
* Monitor key performance indicators (KPIs) like total flights, on-time percentage, total cancellations, and total delays.
* Identify airlines with higher delay frequencies and flight diversions.
* Break down total delay time by primary root causes (Carrier, Weather, Security, NAS, Late Aircraft).
* Pinpoint high-traffic airport hubs with the highest arrival delays.
* Support data-driven decision-making to optimize scheduling and operational strategies.

---

## Tools Used

* **Microsoft Power BI:** Data visualization, interactive reporting, and DAX modeling.
* **Python (Pandas, NumPy):** Data cleaning, missing value handling, and preprocessing large datasets.

---

## Dataset Information

The dataset contains flight-level operational details spanning 2003 to 2017, including:
* **Flight Metrics:** Total Flights, On-Time Flights, Cancelled Flights, Delayed Flights.
* **Airline Details:** Carrier Name, Carrier Code.
* **Delay Categories:** Carrier Delay, Weather Delay, NAS Delay, Security Delay, Late Aircraft Delay.
* **Airport Details:** Origin/Destination Airport Name, Location, Sum of Arrival Delay Minutes.
* **Timeline Data:** Year, Month, Historical Trend Records.

The raw data was cleaned and preprocessed using Python scripts prior to visual modeling in Power BI.

---

## Steps Followed

### 1️⃣ Data Collection & Aggregation
* Gathered historical flight operational datasets covering 19 years of aviation performance.
* Ingested and structured large-scale data for relational modeling.

### 2️⃣ Data Cleaning (Python)
Data cleaning was executed using Python to handle large data volumes effectively:
* Removed duplicate flight records and handled missing values across delay metrics.
* Standardized column headers and data formats (e.g., year formats, airport names).
* Calculated derived metrics for on-time performance and total delay durations.
* Exported optimized clean data files for seamless importing into Power BI.

### 3️⃣ Data Processing & DAX Modeling
Key Performance Indicators (KPIs) and custom measures were established:
* **Total Flights:** 121 Million
* **On-Time Flights:** 96 Million (~79% on-time performance)
* **Total Cancelled Flights:** 2 Million
* **Total Flights Delayed:** 317.52K

### 4️⃣ Dashboard Development
Built a dynamic multi-metric dashboard incorporating:
* **KPI Header Cards:** Quick high-level summary of total flights, delays, on-time counts, and cancellations.
* **Horizontal Bar Charts:** Ranking total delays and diversions across major airlines.
* **Donut Chart:** Visual breakdown of delay causes by percentage.
* **Line Charts:** Historical trend analysis tracking delays from 2003 to 2022.
* **Matrix / Table Views:** Ranking top airport hubs based on total arrival delay minutes.
* **Timeline Slicers:** Dynamic year-wise filtering (2003–2022).

---

## Business Questions Answered

The dashboard answers critical aviation operation questions:
* What is the overall flight volume and on-time performance rate?
* How many flights were cancelled vs. delayed over the 14-year period?
* Which airline experiences the highest total delay count and flight diversions?
* What are the dominant root causes behind flight delays?
* Which airports act as major bottleneck hubs for arrival delays?
* How have flight delay trends shifted year-over-year?

---

## Dashboard Insights

### Overall Operations
Out of **121 Million total flights** analyzed between 2003 and 2022, **96 Million flights were on-time**, while **2 Million flights were cancelled** and **317.52K flights suffered major delays**.

### Root Cause Breakdown
* **Carrier Delays (37.91%)** and **Weather Delays (30.56%)** are the primary contributors, accounting for nearly **70%** of overall delay duration.
* **Late Aircraft Delays (26.12%)** form the third largest factor, demonstrating how early schedule disruptions cascade throughout the day.

### Carrier Performance & Diversions
* **Southwest Airlines Co.** recorded the highest delay volume (**198M**) and the maximum flight diversions (**42K**).
* **American Airlines Inc.** followed as the second highest with **159M** delays and **36K** diversions.

### Top Airport Bottlenecks
* **Chicago O'Hare International (ORD)** generated the highest accumulated arrival delay time (**89.29M minutes**).
* **Atlanta Hartsfield-Jackson International (ATL)** ranked second with **81.59M minutes** of arrival delays.

---

## Skills Demonstrated

During this project, I strengthened my expertise in:
* Large-Scale Data Preprocessing & Cleaning (Python Pandas)
* Data Modeling & Analysis
* DAX Calculations & Measure Creation
* Power BI Interactive Dashboard Design & UI/UX Alignment
* Aviation Domain Metrics & Operational Performance Analytics

---

## Business Impact

This interactive dashboard enables airline operation managers and strategy planners to:
* Monitor overall carrier punctuality and delay frequency.
* Target core delay causes (Carrier vs. Late Aircraft) to improve turnaround workflows.
* Reallocate resources at high-congestion airport hubs like Chicago O'Hare and Atlanta.
* Make data-backed decisions for flight scheduling and buffer planning.

* DASHBOARD -
  <img width="1362" height="722" alt="Airlines_Delay_Performance" src="https://github.com/user-attachments/assets/96e0b1f3-927c-48e6-a995-82e214162d4e" />

