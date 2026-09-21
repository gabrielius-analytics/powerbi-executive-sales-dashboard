# Executive Sales Overview Dashboard

## Project Objective
To provide an interactive, high-level overview of sales performance, revenue tracking, and order metrics, enabling data-driven executive decisions.

## Tech Stack
* **Tool:** Power BI
* **Data Transformation:** Power Query (M Language)
* **Modeling:** Star Schema
* **Calculations:** DAX

## Data Architecture & ETL
* **ETL Process:** Applied comprehensive data cleaning in Power Query (18 transformation steps), including locale-specific type conversions, null handling, and transaction record formatting.
* **Data Modeling:** Implemented a robust Star Schema separating `Fact_Sales` and `Dim_Date` tables to optimize filtering and enable precise Time Intelligence calculations.
* **Measure Management:** Isolated all explicit DAX calculations into a dedicated `_Measures` table for structural clarity.

## Key Features & DAX
* **Time Intelligence:** Quarter-over-Quarter (vs Q3) and Month-over-Month (vs May) dynamic growth indicators.
* **KPI Tracking:** Core business metrics including Total Revenue, Total Orders, and Average Order Value (AOV).
* **Dynamic Visualizations:** Clean, executive-focused UI with interactive filtering by quarters, months, and payment methods.

## Dashboard Previews

<img width="1315" height="801" alt="image" src="https://github.com/user-attachments/assets/5820b1fd-0d93-4cdb-a366-bba8e8f07942" />

<img width="1316" height="800" alt="image" src="https://github.com/user-attachments/assets/47b79c32-d2f1-46c1-b028-a7505c24de71" />

<img width="1318" height="804" alt="image" src="https://github.com/user-attachments/assets/2ad4b6af-6ce9-4085-a2e4-d685968159dd" />
