# Riccardo Franchi

Junior Data Analyst with an engineering background, focused on **analytically correct data modeling and KPI definition**.

I started working on data analysis and data modeling in **November 2025**.  
My work is built as a structured learning and portfolio path based on **end-to-end analytical projects** developed on real-world datasets.

The focus across projects is on:
- data quality validation
- dimensional modeling
- explicit control of data granularity
- KPI design aligned with the analytical grain
- reproducibility and documentation clarity

---

## Core Skills

- **SQL (PostgreSQL)**  
  Analytical queries, JOINs, CTEs, aggregations, basic window functions, time-based analysis

- **Data Modeling**  
  Star schema design, explicit fact table grain definition, dimension normalization, surrogate keys

- **BI & Analytics**  
  KPI definition, normalized metrics, comparative and diagnostic analysis

- **Power BI**  
  Semantic modeling, DAX measures, KPI-driven dashboards

- **Excel / Power Query**  
  ETL, Power Pivot, pivot tables, analytical formulas

- **Documentation & Versioning**  
  Markdown documentation, GitHub-based analytical portfolios

---

## Featured Projects

### NYC Restaurant Inspections — SQL Analytics  
🔗 https://github.com/franchir1/nyc_restaurant_inspections_sql

End-to-end analytical project based on NYC Department of Health and Mental Hygiene (DOHMH) restaurant inspection data.

The source dataset has no stable inspection identifier and allows multiple violations per inspection, requiring explicit modeling decisions.

**Focus areas**
- Star schema modeling with explicit inspection-level grain  
- Fact/dimension design to avoid score duplication caused by violation-level data  
- Layered architecture: STAGING → ANALYSIS → MART  
- Analytical SQL queries for:
  - temporal trends  
  - geographic comparisons  
  - KPI validation  
- Explicit data quality checks and documented assumptions

---

### NYC Restaurant Inspections — Power BI Dashboard  
🔗 https://github.com/franchir1/nyc_restaurant_inspections_powerbi

Semantic modeling and visualization of the same dataset used in the SQL project.

**Focus areas**
- Power Query-based data cleaning and standardization  
- Data model aligned with the analytical star schema  
- DAX measures normalized at inspection level  
- KPI-driven dashboards for:
  - territorial comparison  
  - operational risk analysis  
  - medium-term trends  

---

### US Flights — Flight Delay Analysis (SQL)  
🔗 https://github.com/franchir1/us_flights_analysis_sql

Analytical project based on US DOT On-Time Performance flight data, built to practice fact–dimension modeling and KPI definition.

**Focus areas**
- Fact table grain: one row per operated flight  
- Composite natural key supported by surrogate keys  
- Semantic exclusion of cancelled and diverted flights  
- KPI views for:
  - delay frequency  
  - average arrival delay  
- MART layer prepared for BI consumption

---

### Lending Club Loans — Credit Risk Analysis (SQL)  
🔗 https://github.com/franchir1/lending_club_loans_analysis_sql

Descriptive analysis project focused on understanding loan performance and basic credit risk metrics.

**Focus areas**
- Data cleaning and standardization of financial variables  
- Segmentation by loan grade, term, and purpose  
- KPIs on default rate and exposure  
- SQL written for readability, validation, and learning purposes

---

### Global Electricity Production — Excel & Power Query  
🔗 https://github.com/franchir1/global-electricity-production-powerquery-pivot

Comparative analysis of global electricity production and energy mix.

**Focus areas**
- Power Query-based ETL on multi-country data  
- KPI-oriented aggregation and normalization  
- Long-term trend analysis and cross-country comparison  
- Reproducible analysis using Excel and Power Pivot

---

## Analytical Principles

Across projects, I consistently apply:

- Non-aggregating ETL and early data quality validation  
- Explicit fact table grain definition before analysis  
- KPI normalization using appropriate denominators  
- Verification of analytical assumptions before comparison  
- Clear separation between signal and noise in metrics  
- Separation between raw data, analytical model, and consumption layer  

---

## Background

- **MSc in Materials Engineering and Nanotechnology**  
  Politecnico di Torino

- Professional experience in:
  - Field Service Engineering  
  - Sales Engineering  

with direct exposure to operational data, KPIs, and reporting in industrial contexts.

---

## Contacts

- Email: riccardo.franchi@outlook.com  
- LinkedIn: https://www.linkedin.com/in/riccardo-franchi-b8413a235  
- GitHub: https://github.com/franchir1
