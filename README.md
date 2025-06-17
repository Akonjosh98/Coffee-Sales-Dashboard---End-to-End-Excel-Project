# Coffee Sales Dashboard - End-to-End Excel Project

This project demonstrates an end-to-end Excel solution for transforming raw coffee sales data into a dynamic, interactive dashboard for business insights. It covers data integration, cleaning, advanced formula application, and sophisticated data visualization.

## Project Overview

The aim was to build a comprehensive Coffee Sales Dashboard in Excel to facilitate strategic decision-making by consolidating fragmented sales data into a single analytical tool.

## Key Features

The dashboard provides interactive sales insights through:
*   **Visualizations**: Total Sales Over Time (by coffee type), Sales by Country (U.S., Ireland, UK), and Top 5 Customers.
*   **Interactive Filters**: A timeline for date-based filtering and slicers for Roast Type, Coffee Package Size, and Loyalty Card status.
*   **Professional UI**: Designed for clarity with hidden gridlines, formula bar, and scroll bars (optional) for an app-like feel.

## Core Processes & Techniques

1.  **Data Integration**: Consolidated `Orders` data with `Customers` and `Products` tables. Used **`XLOOKUP`** for customer details and **`INDEX MATCH`** for dynamic product lookups to populate multiple columns efficiently.
2.  **Data Cleaning & Standardization**:
    *   Handled missing email values by replacing zeros from `XLOOKUP` with blanks using nested **`IF`** statements.
    *   Transformed abbreviated codes (e.g., "ROB" to "Robusta", "M" to "Medium") into full names using nested **`IF`** statements for clarity.
    *   Performed duplicate value checks.
3.  **Data Formatting & Structuring**: Standardized date formats (`DD-MMM-YYYY`), formatted sizes (e.g., "1.0 kilo"), and currency (US Dollars for Unit Price and Sales). Converted the raw data into an **Excel Table (`Orders Table`)** for scalability and automatic pivot table updates.
4.  **Calculations**: Calculated `Sales` by multiplying `Unit Price` by `Quantity`.
5.  **Dashboard Development**: Created dynamic **Pivot Tables and Pivot Charts**. Implemented **Timeline and Slicer connections** to link all dashboard visuals for interactive filtering across different sheets.

## Excel Skills Demonstrated

*   **Data Lookup**: `XLOOKUP`, `INDEX MATCH`.
*   **Conditional Logic**: Nested `IF` statements.
*   **Data Aggregation & Visualization**: Pivot Tables, Pivot Charts (Line, Bar).
*   **Interactivity**: Timelines, Slicers, and Report Connections.
*   **Data Management**: Excel Tables (`Ctrl+T`), formatting (custom number formats, currency, dates), and duplicate removal.
*   **Chart Design**: Customizing chart elements, colors, and layouts for professional presentation.

---
