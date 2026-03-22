# Coal’d Blooded Mining Dashboard

🔹**Dataset**

The dataset used for this project can be accessed here: https://lnkd.in/dapxYeH9

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

## 📊 Dashboard Preview

**Operational & Commercial Performance Overview (Overview.png)**
This dashboard provides a comprehensive view of Coal'd Blooded Mining Co.'s operational and commercial metrics. Key highlights include:

- **Ore Mined (MTD)**: 845K tonnes - Total monthly production volume
- **Revenue per Tonne (AUD)**: $106.12 - Financial performance metric
- **Ore per Shift**: 508 tonnes - Average productivity per shift
- **Planned Shift Rate**: 76.10% - Workforce efficiency indicator

**Visualizations**:
- Monthly Ore Production Trend: Shows production fluctuations across the year with an average baseline for comparison
- Ore Production Mix: Donut chart displaying the breakdown across mineral types (Coal 55.56%, Copper 8.27%, Diamond 1.63%, etc.)
- Top 10 Contributors: Ranked list of sites by ore production, with New Laura Shaft leading at 249,938 MTD
- Operational Disruption: Stacked bar chart tracking missed shifts vs unplanned shifts across all months

**Use Case**: This dashboard is ideal for executive and operational managers to quickly assess production performance, identify productivity trends, and benchmark site performance against targets.

---

### Ore Deep Dive - Coal (Ore Deep Dive.png)
A detailed analytical view focused specifically on coal mining operations, providing financial and operational insights:

- **Ore Mined (YTD)**: 6M tonnes - Annual coal production volume
- **Revenue per Tonne (AUD)**: $105.85 - Coal-specific pricing
- **Projected Stockpile Value (AUD)**: $97.31M - Inventory valuation

**Visualizations**:
- Inventory Flow Balance: Dual-axis bar chart comparing sold (invoiced) vs produced (not invoiced) volumes, revealing gaps between production and sales
- Client Invoice Value (YTD) by Payment Status: Detailed breakdown of receivables across 10 major clients, showing overdue, paid, and unpaid amounts with total $588.70M in revenue
- Ranked Site Contribution: Coal production by mining location, with New Laura Shaft contributing 140,260 MTD
- Ranked Extraction Method: Analysis of 12 different mining techniques, led by Boom and Pillar (58,957 MTD) and Drift and Fill (50,155 MTD)

**Use Case**: This report empowers executive and operations teams to track revenue realization, manage cash flow through payment status visibility, and optimize extraction methods based on production efficiency.
