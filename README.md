# Technical-Support-Report --Power-BI-Project
This Power BI report provides a comprehensive view of technical support operations, tracking key metrics such as SLA compliance, agent performance, ticket volumes, and customer feedback. It is designed to help support managers and business analysts monitor service delivery, improve efficiency, and enhance customer satisfaction.

## Dataset used
-<a href="https://github.com/akhilm-ds/Technical-Support-Report---Power-BI Project/blob/main/Technical%20Support%20Dataset.xlsx">Dataset<a/>

## View Report
-<a href="https://github.com/akhilm-ds/Technical-Support-Report---Power-BI-Project/blob/main/Tech%20support.pbix">Report<a/>

## 🎯 Project Objectives

- Track and visualize support KPIs (tickets created, SLA met, resolution time)
- Identify backlog trends and SLA breaches
- Analyze agent workload and performance
- Monitor customer satisfaction through survey results
- Enable data-driven decisions to optimize support operations

- ## 🧭 Report Pages

### 🔹 1. Overview
High-level summary including:
- Created tickets
- Backlog count
- SLA met %
- Average survey score
- Ticket breakdowns by:
  - Status
  - Day type (Weekday/Weekend)
  - Priority
  - Monthly trend

**Filters:**  
Source | Month | Support Level | Priority

---

### 🔹 2. SLA & Resolution Analysis
Detailed resolution and SLA insights:
- Average resolution hours
- SLA breached counts (overall and first response)
- Average agent interactions
- SLA compliance by agent (first response vs. resolution)
- Resolution time by category
- Ticket volume by source
- Peak ticket creation by time & day

Includes a **"Go Back" button** for easy navigation.

---

### 🔹 3. Agent Performance
Agent-level metrics and customer feedback:
- Total number of agents
- Total survey count
- Avg agent interactions
- Avg survey score
- Survey result vs source
- SLA performance per agent (Resolved tickets)
- Feedback count by agent
- Ticket count by support agent
- Survey responses by product group

---

## 📊 Filters & Interactivity

Global filters/slicers:
- **Source**
- **Month**
- **Support Level**
- **Priority**

All pages are fully interactive—clicking on charts will update related visuals.

- ## Report
- <img width="587" height="323" alt="Technical Support _1" src="https://github.com/user-attachments/assets/cef519cc-aab0-4f82-8ba6-cce6c032c57b" />
<img width="590" height="325" alt="Technical Support _2" src="https://github.com/user-attachments/assets/8b8000fd-feb7-4d5d-b7c3-1c012784fb23" />
<img width="585" height="328" alt="Technical Support _3" src="https://github.com/user-attachments/assets/eb9da282-10ec-41dc-8c6a-f3f1928ad7d8" />

## 💡 What I Learned

Working on this project enhanced my knowledge in several key areas:

- **Advanced DAX**: I deepened my skills in writing optimized DAX expressions for KPIs like SLA breached, backlog count, and resolution time.
- **Power BI Design Best Practices**: Learned how to design intuitive, interactive dashboards using slicers, bookmarks, and navigation buttons for a better user experience.
- **Data Modeling**: Strengthened my ability to build a clean and efficient data model that supports cross-page filtering and relational analysis.
- **Performance Optimization**: Explored ways to improve report loading speed through query folding, column reduction, and efficient visuals.
- **Real-World KPI Tracking**: Gained a practical understanding of how to track and interpret service KPIs that align with business goals.


