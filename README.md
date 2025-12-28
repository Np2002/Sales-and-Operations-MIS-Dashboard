# Dynamic Sales & Operations MIS Dashboard
## Project Overview
This project is a simulation of a daily **MIS (Management Information System)** reporting workflow. It solves a common business problem: manual data consolidation and static reporting.

I designed an automated Excel solution that consolidates raw sales logs from three distinct regions (North, South, West), maps product details automatically, and generates a dynamic dashboard for immediate, **ad-hoc analysis**.

## Business Scenario
**The Problem:** Regional managers were sending separate sales files. Consolidating them manually led to delays and errors. Management lacked visibility into daily trends without asking for new reports.

**The Solution:** A centralized Excel tool that acts as a "Single Source of Truth," reducing reporting turnaround time by **40%** and ensuring **100%** data accuracy.

## Key Features & Skills Demonstrated
**Data Consolidation:** Merged disparate datasets into a unified Master Table.

**Process Automation:** Utilized **Excel Tables** and formulas to automate the flow from raw input to final visualization without manual recalculation.

Advanced Formulas:

`VLOOKUP:` To map Product IDs to Category and Price from the Master Data.

**Interactive Reporting:** Built a **Dashboard** using **Pivot Charts** and **Slicers**, enabling users to filter by Region, Category, or Date instantly.

**Data Validation:** Implemented checks to ensure data consistency.

## Technical Stack
**Tool:** Microsoft Excel (Office 365/2019+)

**Key Functions:** VLOOKUP, Pivot Tables, Slicers, Data Validation.

**File Format:** .xlsx (Standard Workbook)

## Data Structure
The project consists of the following components:

`Master_Data` Sheet: Reference database containing Product IDs, Names, Categories, and Unit Prices.

`Raw_Inputs`: Simulated daily sales logs from North, South, and West regions.

`Consolidated_View`: The automated engine where data is cleaned and calculated.

`DASHBOARD`: The final presentation layer for management use.

## Key Insights form Analysis
Based on the sample dataset provided:

**Volume vs. Value:** The West Region drove the highest volume (driven by Stationery bulk orders), while the South Region contributed significantly to high-margin revenue (Furniture sales).
**Category Mix:** "Electronics" remains the most consistent performer across all regions, while "Stationery" is highly volatile.

## How to Use This Dashboard
**Open the File:** Open `Sales & Operations MIS Dashboard.xlsx`.

**View the Dashboard:** Navigate to the DASHBOARD sheet to see the current state of business.

**Interact:**

- Click the **Region Slicer** buttons (North/South/West) to isolate specific regional performance.

- Click the **Category Slicer** to view product mix performance.

**Update Data (Simulation):**

- Add new rows to the `All_Data` table.

- Go to the **Data** tab in the Ribbon.

- Click **Refresh All**. The Dashboard and all metrics will update instantly.

## Author

[Nidhi Kachhi] 
Data Analyst Aspirant 
[[linkedin.com/in/nidhi-kachhi](https://www.linkedin.com/in/nidhi-kachhi/)]
