# Executive Summary

This project builds an analysis-ready inflation dataset in SQL Server using the **U.S. Consumer Price Index (CPI)** time series from **Federal Reserve Economic Data (FRED)** and produces stakeholder-friendly metrics such as **Year-over-Year (YoY) inflation**. The goal is to translate an everyday question—*“Why does everything feel more expensive?”*—into a structured, reproducible analytics workflow that supports consistent reporting, trend monitoring, and decision-making.

I designed a SQL-first pipeline with **data quality controls**, **explicit type handling**, and **time-series calculations** to ensure accurate results (including handling months with **missing CPI values as NULL** rather than hiding gaps). Outputs from SQL will be extended into **Power BI** for executive-ready visuals and narrative insights.


# Business Problem

Inflation affects consumer behavior, budgeting, pricing strategies, and cost forecasting—yet many “inflation conversations” are anecdotal. Stakeholders need a reliable way to answer:

*   **What is inflation YoY right now (headline inflation)?**
*   **Is inflation accelerating or cooling (disinflation)?**
*   **When were inflation spikes most severe historically?**
*   **How should planning assumptions change based on observed trends?**

This project converts CPI time-series data into a repeatable analytics model that supports consistent **YoY inflation reporting**, anomaly detection, and trend interpretation.
