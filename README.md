# CRM Sales Opportunities Analysis Using Excel

## Project Overview

This project analyzes 8,800 sales opportunities to evaluate sales performance, opportunity conversion, product contributions, customer-sector performance, and regional sales results.

The goal is to transform raw CRM data into actionable business insights through data auditing, data preparation, KPI analysis, PivotTables, and an interactive Excel dashboard.

## Business Questions

This analysis explores the following questions:

* What is the historical win rate among closed opportunities?
* How are opportunities distributed across deal stages?
* Which products generate the highest won sales value?
* Which sales agents contribute the most to won sales?
* Which customer sectors contribute the most to won sales value?
* Which regional offices record the highest won sales value?

## Tools Used

* Microsoft Excel
* PivotTables and PivotCharts
* Excel formulas and lookup functions
* Data cleaning and validation
* KPI development and dashboard design

## Data Preparation and Quality Checks

The project included:

* Checking for duplicate opportunity IDs.
* Investigating missing account information.
* Validating engagement and close dates.
* Reviewing missing values in relation to deal stages.
* Enriching opportunity records with relevant sales-team and customer information.
* Standardizing currency formatting and preparing data for analysis.

Missing values were assessed in context rather than automatically treated as errors, because some fields are expected to be blank for open opportunities or records without account information.

## Key Findings

| KPI                 |      Result |
| ------------------- | ----------: |
| Total Opportunities |       8,800 |
| Won Opportunities   |       4,238 |
| Lost Opportunities  |       2,473 |
| Open Pipeline       |       2,089 |
| Historical Win Rate |       63.2% |
| Won Sales Value     | $10,005,534 |

**Historical win rate** is calculated as:

Won Opportunities ÷ (Won Opportunities + Lost Opportunities)

Open opportunities are excluded from this calculation.

### Customer Sector Analysis

The five leading sectors by won sales value were:

| Customer Sector | Won Sales Value |
| --------------- | --------------: |
| Retail          |      $1,867,528 |
| Technology      |      $1,515,487 |
| Medical         |      $1,359,595 |
| Software        |      $1,077,934 |
| Finance         |        $950,908 |

### Regional Performance

| Regional Office | Won Sales Value |
| --------------- | --------------: |
| West            |      $3,568,647 |
| Central         |      $3,346,293 |
| East            |      $3,090,594 |

The West regional office recorded the highest won sales value among the three regions.

## Dashboard Highlights

The Excel dashboard presents key performance indicators and visual analysis of:

* Opportunity distribution by deal stage
* Won versus lost opportunities
* Top customer sectors by won sales value
* Top sales agents by won sales value
* Won sales value by regional office
* Won sales value by product

## Business Value

This project demonstrates how Excel can be used to organize CRM data, monitor sales KPIs, identify differences in sales performance, and present findings in a format that supports business discussions and further investigation.

The results describe the supplied sample dataset and should not be interpreted as verified performance figures for a real-world company.

## Skills Demonstrated

Data Cleaning | Data Validation | Excel | PivotTables | KPI Analysis | Sales Analytics | Dashboard Development | Business Intelligence | Data Storytelling

## About the Project

This is a portfolio project completed using a Maven Analytics sample dataset as part of my development as a data analyst.

My focus is on moving beyond calculations and charts to ask meaningful business questions and communicate insights clearly.
