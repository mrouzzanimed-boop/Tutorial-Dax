

# DAX Learning Path – From Basics to Advanced
 
This repository documents my learning journey through DAX (Data Analysis 
Expressions) in Power BI — starting from foundational functions and 
progressing into more advanced patterns, combining guided tutorial content 
with hands-on practice and problem-solving.
 
## 📺 Reference Tutorial
Based on: [DAX Tutorial](https://www.youtube.com/watch?v=KzGmpyHl-K4)
 
## 📚 Topics Covered
 
### Basic DAX Functions
- **SUM / SUMX** – aggregating values across a column vs. row-by-row iteration
- **CALCULATE** – modifying filter context to compute conditional aggregations
- **FILTER** – returning a filtered table for use in other functions
### Advanced DAX Concepts
- **Context transition** – how CALCULATE converts row context into filter context
- **ALL vs. ALLEXCEPT** – removing filters entirely vs. selectively preserving 
  specific column filters
- **Extension columns** – referencing calculated columns added via 
  ADDCOLUMNS inside further calculations
- **RANKX with ADDCOLUMNS + CALCULATE** – building dynamic ranking measures 
  over a virtual table
- **TOPN** – filtering a table to its top N rows by a given measure, and 
  replicating Power BI's built-in "Top N" visual filter directly in DAX
- **SWITCH(TRUE(), ...)** – multi-condition logic for building dynamic KPI 
  indicators
- **UNICHAR** – generating symbols (▲ ▼ ● ★ ✓) for visual KPI trend indicators 
  on cards, combined with SWITCH(TRUE()) to show direction of change 
  (e.g., delay increasing vs. decreasing month-over-month)
### Time Intelligence
- **Previous month / P2M (period-to-period) comparisons** – comparing 
  current values against the prior month using DATEADD/PREVIOUSMONTH-style logic
- **Year-over-year variation (% change by month)** – calculating month-by-month 
  variation percentages across years
- **Quarter-over-quarter variation (QTS)** – aggregating and comparing 
  performance by quarter
- **Dynamic year slicer** – filtering all visuals by year selection (2021–2024)
- **Running/cumulative totals (TMTD, TQ, TYD)** – month-to-date, quarter-to-date, 
  and year-to-date running calculations
**Example outputs:**
 
KPI cards with trend sparkline and period comparison:

![KPI cards with previous month and P2M comparison]([(https://i.postimg.cc/yNkmDT0P/kpi-cards-example-1.png))

![Monthly variation table with year slicer](https://i.postimg.cc/cxGyMk5Q/monthly-variation-example.png?dl=1)
## 🛠️ What I Did
 
- Followed the tutorial to build a foundation in core DAX syntax and logic
- Worked through real debugging challenges on advanced patterns 
  (ADDCOLUMNS + CALCULATE + RANKX), including troubleshooting environment/
  version-specific issues
- Practiced writing KPI trend measures combining SWITCH(TRUE()) and UNICHAR 
  to visually indicate performance direction on cards
- Applied these concepts toward my own use case: tracking performance metrics 
  and month-over-month trends for a project-monitoring dashboard
## 🎯 Why This Matters
 
DAX is central to building meaningful measures and KPIs in Power BI. This 
repo reflects my hands-on progression from basic aggregation functions to 
more advanced ranking and dynamic visual-indicator patterns — part of my 
ongoing move into data analytics with a civil engineering background.
 
## 🧰 Tools
Power BI, DAX
 


