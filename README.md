*# supply-chain-perfomance-analytics-dashboard-excel
Excel-based Supply Chain &amp; Logistics Performance Dashboard for tracking inventory levels, delivery timelines, vendor performance, and process efficiency using formulas, pivot tables, charts, slicers, and KPI cards.
**# Supply Chain & Logistics Performance Dashboard

An Excel-based analytics project built to monitor and improve supply chain operations by tracking inventory levels, delivery timelines, vendor performance, and process efficiency.

## Project Overview

This project focuses on building an interactive KPI dashboard in Excel using a structured supply chain dataset containing mechanical and industrial products. The dashboard helps analyze warehouse inventory, vendor reliability, delivery performance, and operational bottlenecks.

The main objective of the project is to convert raw operational data into actionable insights and identify opportunities to reduce turnaround time and improve efficiency.

## Problem Statement

Supply chain operations often face challenges such as:
- low stock situations
- delayed deliveries
- poor vendor quality
- slow process stages
- operational bottlenecks

This project was created to monitor these issues through a dashboard and support better decision-making using Excel.

## Goals of the Project

- Track inventory levels across warehouses
- Monitor delivery timelines and delays
- Evaluate vendor performance using lead time and defect rate
- Measure process efficiency using stage time and turnaround time
- Identify bottlenecks affecting operations
- Recommend process improvements to reduce turnaround time
- Automate reporting using Excel formulas and pivot tables

## Dataset Information

The dataset used in this project is a structured sample supply chain dataset created for analysis in Excel.

It contains fields related to:
- inventory management
- delivery performance
- vendor analysis
- process efficiency

### Key columns in the dataset
- `Order_ID`
- `Order_Date`
- `Vendor_Name`
- `Vendor_Lead_Time_Days`
- `Vendor_Defect_Rate`
- `Product`
- `Category`
- `Warehouse`
- `Region`
- `Opening_Stock`
- `Units_Received`
- `Units_Dispatched`
- `Closing_Stock`
- `Reorder_Level`
- `Expected_Delivery_Date`
- `Actual_Delivery_Date`
- `Delivery_Status`
- `Delay_Days`
- `Process_Stage`
- `Stage_Time_Days`
- `Turnaround_Time_Days`
- `Process_Owner`

## Tools Used

- Microsoft Excel
- Excel Formulas
- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting

## Excel Features Used

### Formulas
- `IF`
- `AND`
- `COUNTIF`
- `COUNTA`
- `AVERAGE`
- Logical conditions for KPI tracking

### Analysis Components
- KPI Cards
- Pivot Tables
- Charts
- Slicers
- Conditional Formatting

## Calculated Columns Created

The following calculated fields were added to support dashboard analysis:

- **Inventory_Status**  
  Identifies whether stock is low or sufficient

- **Stock_Gap**  
  Calculates the difference between closing stock and reorder level

- **On_Time_Flag**  
  Marks on-time deliveries

- **Delayed_Flag**  
  Marks delayed deliveries

- **Vendor_Performance_Score**  
  Rates vendor performance based on lead time and defect rate

- **Bottleneck_Flag**  
  Identifies records affected by delays, high turnaround time, low stock, or high defect rate

- **Process_Efficiency**  
  Categorizes process performance as efficient, average, or needs improvement

## Dashboard KPIs

The dashboard includes the following KPIs:
- Total Orders
- Low Stock Items
- On-Time Delivery %
- Average Delay Days
- Average Vendor Lead Time
- Average Vendor Defect Rate
- Average Turnaround Time
- Bottleneck Count

## Dashboard Visuals

### Top Section
KPI Cards:
- Total Orders
- Low Stock Items
- On-Time Delivery %
- Average Delay Days
- Average Vendor Lead Time
- Average Vendor Defect Rate
- Average Turnaround Time
- Bottleneck Count

### Middle Section
- Warehouse Inventory Comparison
- Delivery Performance by Region
- Vendor Performance Comparison

### Bottom Section
- Process Stage Efficiency
- Low Stock Products
- Bottlenecks by Team

## Pivot Table Analysis

The following pivot-based analyses were used:
- Inventory by Warehouse
- Low Stock Items by Product
- Delivery Performance by Region
- Vendor Performance Comparison
- Process Efficiency by Stage
- Bottlenecks by Process Owner

## Business Insights Generated

Using this dashboard, the following insights can be identified:
- warehouses with low stock risk
- products nearing reorder level
- regions with higher delivery delays
- vendors with poor lead time or high defect rate
- process stages contributing to longer turnaround time
- teams associated with repeated bottlenecks

## Recommendations

Based on the analysis, the following improvements can be suggested:
- strengthen reorder monitoring for critical products
- review vendor performance periodically
- reduce delays in quality check and delivery stages
- improve stock planning across warehouses
- monitor bottleneck-heavy teams more closely
- standardize process timelines to reduce turnaround time

## Project Structure
