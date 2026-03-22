# Cold Blooded Mining Dashboard

🔹 **Business Context**

Coal'd Blooded Mining Co. faced several reporting challenges:

- Fragmented data across multiple sources
- Poor visibility into operational performance
- Difficulty identifying inefficiencies in production and equipment usage

The objective was to redesign reporting into a concise, decision-focused dashboard.

---

🔹 **Solution Approach**

- Designed a star-schema-based data model using fact and dimension tables
- Built interactive dashboards focused on:
  - Production performance
  - Equipment utilisation
  - Workforce activity
  - Financial metrics
- Applied data modelling and DAX calculations to derive KPIs

---

🔹 **Data Model**

The solution leverages a structured data model:

**Fact Tables**
- `Fact_Shifts` → Workforce activity and shift tracking
- `Fact_Ore_Volumes` → Production output and ore extraction
- `Fact_Invoices` → Financial transactions and revenue

**Dimension Tables**
- `Dim_Dates` / `Dim_Times` → Time-based analysis
- `Dim_Employees` → Workforce insights
- `Dim_Sites` → Site-level performance
- `Dim_Equipment` → Asset utilisation
- `Dim_Clients` → Customer/revenue analysis

👉 This structure enables scalable, high-performance analytics.

---

🔹 **Key Features**

- 📊 Production vs Target tracking
- ⚙️ Equipment utilisation and downtime analysis
- 👷 Shift and workforce performance insights
- 💰 Revenue and invoice trends
- 📍 Site-level filtering for operational comparison

---

🔹 **Key Insights (THIS is what matters most)**

- Identified low-utilisation equipment, contributing to reduced productivity
- Highlighted inefficient shift patterns impacting output consistency
- Revealed variations in site performance, enabling targeted optimisation
- Improved visibility of revenue trends linked to production output

These insights support operational efficiency, cost control, and better planning.

---

🔹 **Tools & Techniques**

- Power BI (Data modelling, DAX, dashboards)
- Power Query (data transformation)
- Star schema design
- KPI development & performance tracking

---

🔹 **How to Use**

1. Download the .pbix file
2. Open using Microsoft Power BI Desktop
3. Interact with filters and visuals

---

**Dashboard Preview**

[Add dashboard screenshots here]