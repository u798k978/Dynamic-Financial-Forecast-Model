# Dynamic-Financial-Forecast-Model

**Project Overview:**

This repository contains a comprehensive 5-Year Financial Projection Model for Falcon Manufacturing, a simulated company in the manufacturing sector.

The model follows best practices, separating Inputs/Assumptions from the Revenue/Cost Drivers and Final Financial Statements & Valuation Metrics. It is designed to be fully dynamic, allowing users to easily modify core assumptions and instantly see the impact on projected revenue, costs, and key performance indicators (KPIs) over the forecast period (e.g., 2025–2029).

This project can be used for financial analysis, business valuation practice, and data visualization.

**File Structure:**

The files are organized into two main categories: the Core Financial Model (outputs and drivers) and Raw Data (detailed inputs). All files are provided in CSV format, extracted from their original Excel workbooks.

1. Core Financial Model (Outputs & Drivers) - These files represent the key logic, drivers, and final outputs of the 5-Year Financial Model (Financial_Model_Falcon_Manufacturing.xlsx).

Financial_Model_Falcon_Manufacturing.xlsx - Assumptions.csv	Contains the core, high-level economic and financial assumptions that drive the entire model, such as Base Revenue, Growth Rate, COGS %, OPEX %, Tax Rate, and Depreciation.
   
Financial_Model_Falcon_Manufacturing.xlsx - Revenue Model.csv	The detailed top-line revenue breakdown by product (Alpha, Bravo, Charlie, Delta) for each of the five forecast years. This shows the calculation of total revenue based on the growth assumption.

Financial_Model_Falcon_Manufacturing.xlsx - Costs & Opex.csv	The projected Cost of Goods Sold (COGS), Operating Expenses (Opex), and Depreciation over the five-year period. These figures are calculated based on the percentages specified in the Assumptions file.

Financial_Model_Falcon_Manufacturing.xlsx - Financial Statements.csv	The summary Income Statement for the five-year forecast, showing the calculation flow from Revenue to EBIT, Tax, and finally Net Income.

Financial_Model_Falcon_Manufacturing.xlsx - KPI Dashboard.csv	A summary of key Valuation and Performance Metrics, including Revenue CAGR, Average Net Margin, and the Net Present Value (NPV) and Internal Rate of Return (IRR) based on the projected Free Cash Flow (FCF).

2. Raw Data & Detailed Input - These files contain the underlying granular data used to inform or validate the assumptions in the core model (RawData_Falcon_Manufacturing.xlsx).

   RawData_Falcon_Manufacturing.xlsx - Assumptions.csv	A redundant copy of the high-level model assumptions, likely stored in a dedicated raw data sheet to ensure    consistency in the original Excel structure.
   
   RawData_Falcon_Manufacturing.xlsx - Product_Monthly_Sales.csv	Granular, month-by-month sales data for each product, including Units Sold, Average Price, and total monthly Revenue. This data would be used to validate or project the annual figures used in the Revenue Model.


**Tech & Formulas:**

- Excel functions: `SUM`, `AVERAGE`, `POWER` (CAGR), `NPV`, `IRR`  
- Linked cells across sheets, charts (Bar/Line), conditional formatting.


   
