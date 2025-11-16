# **🏥 Healthcare Provider Financial Insights Dashboard**

**Transforming complex healthcare billing into clear, actionable intelligence.**

## **📚 Table of Contents**
1.Dashboard Preview

2.Live Demo

3.The Story Behind the Dashboard

4.Key Features

5.How It Works

6.Tech Stack

File Structure

## **📸 Dashboard Preview**
<img width="2255" height="1270" alt="image" src="https://github.com/user-attachments/assets/8644a324-9a25-40b9-bb3e-5fd555ae24a1" />

##  **🎬 Live Demo**
![Healthcare Dashboard Demo](https://github.com/archies33/Healthcare-Provider-Dashboard/blob/main/GIF.gif)

## **📖 The Story Behind the Dashboard**

Every healthcare provider handles an enormous volume of billing data—medications, procedures, room charges, diagnostics, insurance claims, and more.
But while the data is rich, the insights often aren’t. Leaders jump between reports, spreadsheets, and systems, trying to stitch together a financial picture that never quite feels complete.

So this dashboard was designed with one goal:

**Turn overwhelming financial data into a simple, trustworthy story.**

Instead of scattered numbers, executives now get a clear and interactive financial overview:

* Where the hospital’s money is coming from
* Where it’s being spent
* Which departments and procedures drive revenue
* How insurance vs. out-of-pocket payments actually break down
* How costs vary across locations, diagnoses, and service types

Behind the polished visuals is a carefully modeled Power BI report driven by dynamic DAX measures, a custom date table, and clean transformations—all working together to produce a dashboard that is both reliable and easy to explore.

This isn’t just a report.
It’s a financial command center for healthcare decision-makers.

## **🔥 Key Features**
**1. Executive-Level KPI Cards**

Quick insights into total billing, medication costs, treatment costs, insurance coverage, and out-of-pocket amounts.

**2. Geographic Revenue Breakdown**

A city/state toggle lets users instantly see which regions contribute most to revenue.

**3. Procedure Revenue Analysis**

A dual-metric view showing both billing amount and each procedure’s % share of total revenue.

**4. Diagnosis & Service Type Breakdown**

A 100% stacked chart visualizes exactly which services drive cost for each diagnosis.

**5. Department Performance Comparison**

A side-by-side view of revenue by department with relative contribution percentages.

**6. Intelligent Interactivity**

Slicers and bookmarks allow users to switch between summarized and detailed views effortlessly.

## **🧠 How It Works**
**Data Modeling & Preparation**

* Custom date table built using CALENDARAUTO()

* Added time intelligence fields (Year, Month, Quarter)

* Cleaned & standardized cost and billing fields

**Core DAX Measures**

* Total Costs

* Billing Amount

* Insurance Coverage

* Out-of-Pocket Costs

* Patient-level Averages

## **Visualization Layer**

Each chart is designed to answer a specific business question—quickly, clearly, and visually.

## **🛠️ Tech Stack**
| Component          | Technology                            |
| ------------------ | ------------------------------------- |
| Data Visualization | **Power BI**                          |
| Data Modeling      | **DAX**, calculated tables            |
| Data Source        | CSV/Excel or hospital billing exports |
| Data Preparation   | Power Query (M Language)              |
| Time Intelligence  | Custom Date Table                     |

