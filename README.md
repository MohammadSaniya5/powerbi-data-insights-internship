<p align="center">
  <img src="https://github.com/MohammadSaniya5/powerbi-data-insights-internship/blob/main/banner.png" alt="Power BI Internship Banner" width="100%">
</p>

# YuvaIntern – Power BI Internship
![Internship](https://img.shields.io/badge/Internship-YuvaIntern%20%2B%20NSDC-blue)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-Student%20Project-lightgrey)

This repository contains my weekly submissions for the Power BI Data Insights Internship conducted by YuvaIntern. Each week focuses on a different stage of building a data-driven solution using Power BI.

---

## Week 1: Data Strategy and Planning

### Task Objective
Develop a comprehensive Power BI data strategy plan for an education use case.

### Deliverables
- Defined business objectives  
- Identified public data sources  
- Data preparation and integration roadmap  
- Power BI tool usage and planning  
- A conceptual star schema (included inside the report)

### File
- Week1_Data_Strategy_MohammadSaniya.docx.pdf

### Tools Used
- Power BI Desktop  
- Power Query Editor  
- DAX  
- Data Modeling

---

## Week 2: Data Modeling and Integration

### Task Objective
Build a Power BI data model by integrating multiple datasets (student performance and attendance) using Power Query, and design a relational schema to support analysis.

### Deliverables
- Cleaned and transformed data using Power Query  
- Defined data types: text, decimal, date/time  
- Created a star schema with:
  - Students (dimension)  
  - Performance and Attendance (fact tables)  
- Established one-to-many relationships  
- Applied DAX measures for score and attendance analysis  
- Documented key issues (nulls, date formats, duplicates) and their solutions

### Files
- Week2_Data_Modeling_Polished.docx

### Tools Used
- Power BI Desktop  
- Power Query Editor  
- DAX  
- Data Modeling (Star Schema)

---
## Week 3: Dashboard Design Fundamentals

### Task Objective
Design a dashboard layout based on the Week 2 data model for student performance and attendance. The focus is on creating an intuitive, interactive, and goal-driven Power BI dashboard.

### Deliverables
- Dashboard layout plan (top-down structure)
- Sketch (handmade-style image mockup)
- Visual element mapping with business objectives
- Detailed explanation of:
  - KPI Cards
  - Bar/Line/Pie Charts
  - Matrix Table
- Interactivity: slicers, drill-down, tooltips
- Design principles: color coding, font hierarchy, layout balance

### Files
- week3_Dashboard_design_Mohammad_Saniya.pdf  

### Tools Used
- Power BI (conceptual)
- Canva / Python (for mockup sketch)
- MS Word (for documentation)
  
---
## Week 4: Advanced Analytics and Custom Visuals

### Task Objective
To simulate real-world Power BI usage by applying advanced analytics techniques, including complex DAX formulas and custom visuals, layered on top of an existing academic data model.

### Business Scenario
Identify students who are underperforming due to consistently low attendance and support early intervention strategies using visual and analytical insights.

### Advanced DAX Measures
- `AtRiskFlag`: Flags students with <75% attendance AND <40% score.
- `AttendanceTrend`: Calculates average attendance trend over the last 3 months.
- `ScoreZScore`: Highlights outliers in score distribution.
- `CountAtRiskStudents`: Dynamic KPI to track total risk cases.

### Custom Visuals Used
- Bullet Chart (OKViz): Score vs. target performance
- Radar Chart (Microsoft): Skill gap comparison across subjects
- Decomposition Tree: Drill-down from Class → Student → Risk flag
- Hierarchy Slicer: Multi-level filtering by class, gender, subject

### Key Learnings
- Linked DAX measures to visuals via Power BI’s star schema model.
- Integrated advanced visuals to uncover actionable trends.
- Simulated real-school use cases for early intervention and resource planning.

### Files
- Week4_Advanced_Analytics_MohammadSaniya.pdf
---

## Week 5: Performance Optimization and Report Enhancement

### Task Objective
To optimize Power BI reports and data models for faster load times, cleaner visuals, and real-world usability. The goal was to simulate industry practices like query tuning, visual streamlining, and performance validation.

### Key Optimizations Applied
- **Query Folding**: Applied in Power Query to reduce memory load  
- **Incremental Refresh**: Enabled on Attendance table to speed up updates  
- **Aggregation Tables**: Used to pre-summarize KPIs by class/subject  
- **Optimized DAX**: Rewrote formulas using `VAR` to reduce calculation time  
- **Model Simplification**: Removed unused columns and unnecessary relationships  
- **Auto Date/Time Disabled**: Improved memory and responsiveness

### Visual & UX Enhancements
- Reduced slicer overload  
- Used **bookmarks** to toggle visual sections  
- Added **tooltips** instead of on-screen clutter  
- Reorganized visuals across multiple pages

### Before vs After (Estimated)
| Metric              | Before        | After       |
|---------------------|---------------|-------------|
| Refresh Time        | ~2 mins       | ~45 sec     |
| Visual Load Time    | 5–6 sec       | 1–2 sec     |
| Memory Usage        | High          | Optimized   |
| DAX Complexity      | Repetitive    | Optimized   |

### Files
- Week5_Performance_Optimization_MohammadSaniya.pdf
---
 ## Week 6: Final Evaluation and Presentation of Data Insights

### Task Objective
Compile and present the complete Power BI internship journey — from data strategy to dashboard optimization — in a final report. Demonstrate how data insights can drive academic decision-making.

### Deliverables
- Executive summary of the overall project  
- Week-wise methodology recap  
- Key insights and performance findings  
- Documented challenges and resolutions  
- Future recommendations for enhancing dashboards  
- Real-world case study for actionable intervention

### File
- Week6_Final_Report_Mohammad_Saniya.pdf

### Tools Used
- Power BI Desktop  
- Power Query Editor  
- DAX (CALCULATE, VAR, RANKX, FILTER)  
- Custom Visuals (Bullet Chart, Radar Chart, Decomposition Tree)

---

## Completion Summary

Over the course of 6 weeks, this internship provided hands-on experience with end-to-end Power BI development — from building a strategic data plan to optimizing a fully interactive dashboard. Each week focused on a core data analytics skill:

- Week 1: Strategic planning for data use in education
- Week 2: Data modeling and relationship building
- Week 3: Designing impactful dashboards
- Week 4: Applying advanced analytics and custom visuals
- Week 5: Optimizing performance and report responsiveness
- Week 6: Presenting final insights and strategic recommendations

This repository showcases my complete Power BI journey — including business goals, technical implementations, and insights that can drive real-world academic decisions. The project was executed under the **YuvaIntern + NSDC Virtual Internship Program**, and is now a proud part of my data analytics portfolio.

### Certificate of Completion (coming soon)

---

Feel free to explore the reports and leave feedback or suggestions!


