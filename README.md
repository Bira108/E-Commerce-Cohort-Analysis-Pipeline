# E-Commerce Dynamic Cohort & Retention Pipeline

## Project Overview
This project establishes an automated ELT pipeline using Databricks to answer the core business question: **How long does it take for customers to return for a second purchase?**

## The Architecture
We implemented a **Medallion Architecture**:
- **Bronze:** Raw transactional ingestion.
- **Silver:** Data cleaning and validation.
- **Gold:** Cohort and Retention metric aggregation.

## Key Insights
- Successfully integrated 1,000+ incremental records from 2025.
- Identified an average retention window of [X] days for 2024 baseline.
- Observed a loyalty migration where repeat purchase depth improved year-over-year.

## Tools Used
- **Databricks** (PySpark/SQL)
- **Delta Lake**
- **Medallion Architecture**

## Dashboard View in Databricks

(https://rb.gy/p7bymc)
