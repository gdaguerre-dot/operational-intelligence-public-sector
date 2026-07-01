# Operational Intelligence for Public Sector Digital Transformation

### Business Intelligence | IT Service Management | Power BI | SQL | Data Analytics

**Consulting-Style Business Intelligence Case Study**

## Executive Summary

This project transforms operational data from an enterprise issue tracking system into strategic management information for decision makers.

Using historical service desk records from a large-scale public sector digital transformation project, the analysis focuses on measuring operational performance, identifying process bottlenecks and supporting continuous service improvement through Business Intelligence.

Rather than analyzing individual incidents, the objective is to understand how the IT service performs as a whole.

---
---

## Project Approach

This repository follows a consulting-oriented Business Intelligence methodology designed to transform operational IT service data into strategic information for decision makers.

Rather than focusing solely on dashboard development, the project documents the complete analytical lifecycle used in Business Intelligence consulting engagements.

## Analytics Methodology

The project is structured into seven analytical phases.

### Phase 1 — Business Understanding

Define the business context, stakeholders, business objectives and analytical questions.

### Phase 2 — Exploratory Data Analysis (SQL)

Understand the operational dataset through descriptive analysis, data profiling and exploratory SQL queries.

### Phase 3 — Data Preparation

Assess data quality, clean operational records and prepare the dataset for analytical modeling.

### Phase 4 — Dimensional Modeling

Design a Star Schema optimized for Business Intelligence and executive reporting.

### Phase 5 — Dashboard Development

Create executive dashboards focused on operational performance, IT Service Management and decision support.

### Phase 6 — Executive Reporting

Document findings, KPIs, business recommendations and analytical conclusions.

### Phase 7 — Executive Storytelling

Translate analytical findings into strategic insights understandable by business stakeholders.

# Business Problem

Large digital transformation projects generate thousands of operational incidents across multiple functional areas, development teams and support groups.

Although issue tracking platforms store detailed operational information, managers often lack executive-level visibility regarding:

- operational workload
- service performance
- process efficiency
- resource allocation
- recurring issues
- project evolution

Without analytical reporting, decision making becomes reactive instead of proactive.

---

# Business Question

**How can operational incident data be transformed into actionable intelligence that improves IT service management and supports decision-making during a large public sector digital transformation project?**

---

# Business Objectives

The project aims to:

- Measure operational workload.
- Monitor incident resolution performance.
- Identify critical modules generating the highest number of incidents.
- Detect recurring operational problems.
- Evaluate workload distribution across projects and teams.
- Analyze service evolution over time.
- Support continuous improvement initiatives.

---

# Analytical Questions

The analysis answers questions such as:

- Which projects generate the highest operational workload?
- Which modules produce the largest number of incidents?
- Which incident categories consume the most effort?
- Which priorities remain unresolved for the longest time?
- Where does operational rework occur?
- How has operational activity evolved throughout the project lifecycle?
- Which processes present the greatest improvement opportunities?

---

# Dataset

The dataset consists of historical incident records exported from a Redmine issue management platform used during a public sector digital transformation initiative.

Each record contains operational information including:

- Incident ID
- Project
- Tracker
- Status
- Priority
- Category
- Assigned Team
- Creation Date
- Closing Date
- Estimated Hours
- Spent Hours
- Resolution Time
- Author
- Assignee

---
Business Understanding

↓

SQL Exploration

↓

Data Quality Assessment

↓

Data Preparation

↓

Dimensional Modeling

↓

KPI Definition

↓

Power BI Dashboard

↓

Executive Storytelling

↓

Business Recommendations

# Data Model

The project follows a dimensional modeling approach using a Star Schema.

### Fact Table

FactIncidents

### Dimension Tables

- DimDate
- DimProject
- DimStatus
- DimPriority
- DimCategory
- DimPerson
- DimTracker

---

# Technologies

- Power BI
- Power Query
- DAX
- SQL
- Dimensional Modeling
- Business Intelligence
- Data Visualization

---

# Dashboard Structure

## Executive Dashboard

KPIs

- Total Incidents
- Open Incidents
- Closed Incidents
- Resolution Rate
- Average Resolution Time
- Critical Incidents
- Operational Workload
- Rework Indicator

---

## Operational Performance

- Incidents by Project
- Incidents by Module
- Incidents by Priority
- Pareto Analysis
- Operational Heatmap

---

## Process Analytics

- Lead Time
- Cycle Time
- Estimated vs Actual Hours
- Backlog Analysis
- SLA Monitoring

---

## Continuous Improvement

- Root Cause Analysis
- Most Critical Modules
- Operational Bottlenecks
- Improvement Opportunities

---

# Key Insights

The dashboard enables managers to:

- Monitor operational performance in real time.
- Detect service bottlenecks.
- Prioritize improvement initiatives.
- Optimize resource allocation.
- Support data-driven decision making.
- Increase visibility across projects.

---

# Repository Structure

```text
Operational-Intelligence-Public-Sector/

│
├── README.md
│
├── data/
│     ├── raw/
│     │      incidents_raw.csv
│     └── processed/
│
├── sql/
│     ├── 01_business_understanding.sql
│     ├── 02_exploratory_data_analysis.sql
│     ├── 03_data_quality.sql
│     ├── 04_dimensional_model.sql
│     └── 05_kpi_queries.sql
│
├── powerbi/
│     └── Operational_Intelligence.pbix
│
├── pdf/
│     └── Operational_Intelligence_Case_Study.pdf
│
├── images/
│     ├── business_workflow.png
│     ├── star_schema.png
│     ├── executive_dashboard.png
│     ├── operational_dashboard.png
│     ├── process_analytics.png
│     └── storytelling.png
│
└── LICENSE
```

---

# Business Value

This project demonstrates how Business Intelligence techniques can transform operational IT data into strategic information that supports continuous improvement within public sector digital transformation initiatives.

The analytical approach can be adapted to:

- IT Service Management (ITSM)
- PMO reporting
- Digital Transformation Offices
- Shared Service Centers
- Operational Excellence programs

---

# Author

**Gerónimo Daguerre**

Business Intelligence | Data Analytics | Digital Transformation | Process Improvement

LinkedIn:
https://www.linkedin.com/in/gerodaguerre/

GitHub:
https://github.com/gdaguerre-dot
