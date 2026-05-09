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

## Dashboard View (Databricks)

[View Dashboard](https://rb.gy/p7bymc)

## Visualizations

**Cohort Size Chart (2024 only)**
<br>
<br>
<img width="699" height="400" alt="Cohort Size Chart (2024   2025)" src="https://github.com/user-attachments/assets/52b05607-f882-429f-ae6b-5f00c6f635a6" />
<br>
**Cohort Size Chart (2024 & 2025)**
<br>
<br>
<img width="699" height="400" alt="Cohort Size Chart (2024 only)" src="https://github.com/user-attachments/assets/40c50887-072e-4311-9928-78aa83601443" />
<br>
**Retention to 2nd Purchase (2024 & 2025)**
<br>
<br>
<img width="699" height="400" alt="Retention to 2nd Purchase (2024   2025)" src="https://github.com/user-attachments/assets/74c6ece1-fde0-44b0-8c33-8eaf71849807" />
<br>
**Retention to 2nd Purchase (2024 Only)**
<br>
<br>
<img width="699" height="400" alt="Retention to 2nd Purchase (2024 Only)" src="https://github.com/user-attachments/assets/115f55db-7a5a-4936-8d98-5301dd0b3f9c" />
<br>
**Repeat Purchase Depth (2024 & 2025)**
<br>
<br>
<img width="699" height="400" alt="visualization Repeat Purchase Depth (2+, 3+, 4+) 2024   2025" src="https://github.com/user-attachments/assets/d87996ef-1d5c-458f-b20a-a5a2d5447e71" />
<br>
**Repeat Purchase Depth (2024 Only)**
<br>
<br>
<img width="699" height="400" alt="visualization Repeat Purchase Depth (2024 Only)" src="https://github.com/user-attachments/assets/58e0d2e5-00c5-4650-bb3a-2f1242c35357" />
<br>

