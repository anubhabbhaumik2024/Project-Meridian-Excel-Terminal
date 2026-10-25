# Project-Meridian-Excel-Terminal
Integrated Valuation, Risk and Control Terminal built in Excel 
 About the Project
Project Meridian is a comprehensive financial, risk, and control terminal built end-to-end in **Excel for the Web**. It models a single listed Indian company using a single workbook to cover corporate finance, equity research, FP&A, credit, tax, and audit analytics.

This project demonstrates advanced financial modeling, data engineering, and analytics without relying on VBA, utilizing modern Excel features like Power Query, Dynamic Arrays, LAMBDA functions, and the Data Model.

## Key Features
* **Comprehensive 3-Statement Model:** Fully linked Income Statement, Balance Sheet, and Cash Flow statement with circular interest toggles.
* **Valuation & Scenarios:** 
  * WACC build-up, DCF (Gordon Growth & Exit Multiple), Sum-of-the-parts (SOTP), and Comps.
  * Three integrated scenarios (Base, Bull, Bear) feeding a central Control Panel.
* **Advanced Risk Analysis:** Correlated Monte Carlo simulations (1,000+ runs) for probabilistic valuation.
* **FP&A & Control:** Budget vs. Actual variance analysis, Price-Volume-Mix (PVM) bridges, and rolling forecasts.
* **Audit & Tax Analytics:** Benford's law testing, duplicate finding, outlier detection, and GST GSTR-2B reconciliation.
* **Executive Dashboard:** Live CUBE formula-driven KPIs, dynamic narrative generation, and a print-ready board pack.

## Technical Stack
  **Platform:** Microsoft Excel for the Web
  **Data Ingestion:** Power Query (M) parameterised queries
  **Formulas:** Dynamic Arrays (FILTER, SORT, SEQUENCE), LAMBDA library (MAP, REDUCE, SCAN)
  **Data Modeling:** Power Pivot / Data Model (DAX)
  **Automation:** Office Scripts (TypeScript) for scenario running

## Project Roadmap (8-Week Build)
**Tier 1 (Core):** Control Panel, Assumptions, Schedules, 3 Statements, Valuation, Sensitivity, Checks, Dashboard.
**Tier 2 (Advanced):** Power Query Data pipelines, Ratios & Peers, FP&A Variance, Tax & GST, SOTP, Board Pack.
**Tier 3 (Elite):** Custom LAMBDA library, Monte Carlo, LBO, Optimisation, Audit Analytics, Office Scripts.


