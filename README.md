# Hospital Patient Analytics Dashboard — Power BI Project

## Overview
This project is an interactive Power BI dashboard built on a healthcare dataset 
sourced from Kaggle. It analyzes patient demographics, hospital admissions, 
billing patterns, and medical condition trends across 55,500 patient records.

## Video Walkthrough
[Watch the full project walkthrough here](https://drive.google.com/file/d/1QQxpE-OlV26Yss-DkI9NgwXr7a0sPFWm/view?usp=drive_link)

## Dataset
- **Source**: [Healthcare Dataset by Prasad Patil (Kaggle)](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)
- **Records**: 55,500 patient rows, 15 original columns
- **Supplementary file**: `Condition_Dept_Lookup.csv` — a manually created lookup 
  table mapping each Medical Condition to a Hospital Department, used to enrich 
  the main dataset via Merge Queries.

## What This Project Demonstrates
- **Power Query (ETL)**: data profiling, text/number/date transformations, 
  custom columns, conditional columns, index columns
- **Data Modeling**: grouping/aggregation, merge queries, pivot & unpivot, 
  append queries, folder connector concepts, and reusable parameters
- **DAX-free calculated columns**: billing correction, length of stay, 
  age/billing/stay/risk categorization
- **Report Design**: KPI cards, bar/line/donut charts, slicers, page-level 
  and visual-level filters, cross-filtering interactions
- **Multi-page reporting**: Dashboard Overview, Patient Detail, and Billing 
  Analysis pages, styled with a consistent theme

## Files in This Repository
| File | Description |
|---|---|
| `healthcare_dataset.csv` | Main patient records dataset (source: Kaggle) |
| `Condition_Dept_Lookup.csv` | Manually created lookup table (Medical Condition → Department) |
| `Project_2.pbix` | Final Power BI project file |

## Key Insights
- Patient count and revenue distribution across hospitals and medical conditions
- Monthly admission trends segmented by year
- Insurance provider coverage distribution
- Billing tier and risk classification based on test results and treatment cost

## Tools Used
- Power BI Desktop
- Power Query Editor (M language)
- Kaggle (data source)

## Author
Riya Gokani
