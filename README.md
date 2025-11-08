# Return-Performance-YoY-Analysis

## 📊 Project Overview

This Power BI project analyzes Return Performance and Year-over-Year (YoY) trends to understand how employee performance and product returns have changed over time.
The dashboard provides a clear view of return counts, average return values, and return rates — all compared YoY to highlight performance improvements or declines.

## 📊 Dashboard Preview  
![Return Performance Dashboard](./Screenshot%202025-11-08%20182244.png)  


## 🎯 Objective

To build a Power BI dashboard that delivers actionable insights on:

Total and average returns over time

YoY growth and percentage changes

Employee-wise return contributions

Monthly return trends with YoY comparison

## 🧩 Datasets Used

Orders.xlsx

People.xlsx

Returns.xlsx

All datasets were cleaned, transformed, and modeled to form a star schema in Power BI.
A Date Table was created and marked as the official date dimension for time intelligence functions.

## ⚙️ Data Modeling & DAX

The model follows a star schema with relationships among Orders, People, and Returns.
Key DAX measures created:

Return Rate % = (Number of Returns / Total Transactions)

Avg Return Value = AVERAGE(Returns[Return Value])

YoY calculations using SAMEPERIODLASTYEAR() and DATEADD()

Dynamic Top N Employees by Return Count

Monthly Return Trend with YoY overlay

## 🎨 Dashboard Features

KPI Cards: Total Returns, Avg Return Value, Return Rate %, and YoY % change indicators.

Donut Chart: Employee contribution to total returns (%).

Bar Chart: Top 4 employees by return count.

Line Chart: Monthly return trend with YoY comparison.

Slicers: Year, Person, and Region for easy filtering.

“Clear Filters” Button: For better interactivity and user experience.

## 🔍 Key Insights

Total Returns: 297 | Last Year: 114

YoY Avg Return Value: -7.71% (slight drop compared to last year)

YoY Return Rate: +3.3% improvement

Top Contributor: Anna (61.5% of total returns)

Performance trends indicate improved process efficiency despite minor fluctuations in return values.

## 🎥 Video Presentation

▶️ YouTube Walkthrough: Watch Here: https://www.youtube.com/watch?v=15xtNI0gRvg

The video explains:

Data cleaning and model design

DAX measures and YoY logic

Dashboard walkthrough and insights

## 🧰 Tools Used

Microsoft Power BI – Dashboard creation and analysis

Power Query Editor – Data cleaning & transformation

DAX – Calculations and YoY analysis

## 🏁 Outcome

A clean, interactive Power BI dashboard that effectively communicates performance insights and YoY trends.
It enables stakeholders to track improvement areas, evaluate employee contributions, and make data-driven decisions.

