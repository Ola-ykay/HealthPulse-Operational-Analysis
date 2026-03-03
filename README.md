# HealthPulse Operational Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Tools and Features Used](#tools-and-features-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [KPIs](#kpis)  
- [Insights](#insights)
- [Business Impacts](#business-impacts)
- [Data Snapshots](#data-snapshots)
- [Conclusion](#conclusion)

## Project Overview
HealthPulse is a multi-clinic healthcare network operating 15 clinics across the Austin metro area, serving over 100,000 patients annually. As the organization scaled, operational inefficiencies began affecting revenue, provider workload balance, and patient experience.
This project delivers a centralized analytics solution designed to:
- Reduce patient no-show rates
- Optimize provider utilization

## Problem Statement
As HealthPulse clinic network scales across 15 clinics, operational inefficiencies are increasing including high no-show rates, and uneven provider utilization
To support data-driven decision-making, this analysis aims to answer the following critical business questions:
- What is the overall no-show rate across the network?
- Are no-show rates increasing or decreasing over time?
- Which age groups are most likely to no-show?
- Does insurance type influence appointment attendance?
- Are providers evenly utilized across clinics?
- Which specialties are operating above safe capacity (>90%)?
- Which providers or clinics are underutilized (<60%)?

## Tools and Features Used
Microsoft Power BI
I applied all these features in this project:
- Data cleaning and transformation
- DAX formulas (measures and calculated columns)
- conditional formatting

## Data Cleaning and Preparation
The dataset consisted of five primary tables:
- patients
- providers
- clinics
- appointments
- dates

Key Cleaning Steps:
- Removed duplicate appointment records
- Splitted date into day, month and year
- Converted No_Show column (0/1) into analytical format
- Handled null values
- Created Age Groups for demographic analysis

## The following KPIs were developed to monitor operational and financial performance:
- Total Appointments
- No-Show Rate (%)
- Provider Utilization (%)
- Average Wait Time

