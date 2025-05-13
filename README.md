# DataBeachHouse Forecasting Models

## Project Overview

**Sponsor**: [Blue Nalu Analytics](https://www.bluenaluanalytics.com)  
**Team**: Gibson Weber, Sooji Rhodes, Chris Oxner, Derek Pederson  
**Course**: UNC MADS Capstone Project – Summer 2025  

---

## Problem Statement

Blue Nalu Analytics, a data consultancy based in North Carolina, supports small and mid-sized businesses in using their data more effectively. Our capstone team will assist Blue Nalu in generating actionable forecasts and visualizations to help business clients better understand reservation patterns, customer behavior, and related operational trends. The project is exploratory by nature but centers on producing forward-looking models and recommendations using historical data.

---

## Project Objectives

- Analyze reservation and booking trends from historical data
- Build predictive models with a short-term forecast horizon (1–4 weeks out)
- Identify correlations and patterns that inform business decisions
- Develop Tableau or Excel-based dashboards for insight delivery
- Create clear and actionable recommendations for small business clients

---

## Data Plan

**Primary Data Source**:  
- Historical reservation/booking data provided by Blue Nalu Analytics  
- Time series data with seasonal/short-term variations

**Key Data Tasks**:
- Cleaning and preprocessing (date/time parsing, missing value imputation)
- Feature engineering (e.g., time-of-day, day-of-week, lead time)
- Exploratory data analysis to uncover trends and anomalies

---

## Methodology

- **Exploratory Data Analysis** using RStudio
- **Predictive Modeling** using statistical and machine learning techniques:
  - Linear regression
  - Exponential smoothing / ARIMA
  - XGBoost or Random Forest (if appropriate)
- **Visualization** using Tableau dashboards
- **Version Control** using GitHub (code, analysis, deliverables)

---

## Timeline & Milestones

| Week | Task |
|------|------|
| Week 1-3 | Kickoff meeting, define scope, access data |
| Week 3-5 | Clean and explore data |
| Week 5-8 | Build and test forecasting models |
| Week 9-10 | Create and iterate on visualizations |
| Week 11 | Finalize deliverables and presentation materials |
| Week 12 | Public presentation and sponsor wrap-up |

---

## Deliverables

- [ ] Cleaned and documented dataset (anonymized as needed)
- [ ] Forecasting models + code (with evaluation metrics)
- [ ] Tableau dashboard(s) or Excel-based visual insights
- [ ] Public-facing project page with visualizations and findings
- [ ] Final presentation deck and executive summary

---

## Repository Structure

```bash
├── data/                # Cleaned and raw datasets (excluded from version control if sensitive)
├── notebooks/           # Jupyter notebooks for EDA and modeling
├── scripts/             # Python scripts for preprocessing and model pipelines
├── visuals/             # Charts and dashboard screenshots
├── deliverables/        # Final presentation, summary reports
├── README.md            # Project overview and documentation
└── requirements.txt     # Python dependencies
