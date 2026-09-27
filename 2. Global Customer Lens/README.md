## Global Customer Lens

### Overview
A two-view Power BI dashboard tracking revenue, gross profit, and budget performance for a B2B energy / oilfield-services customer base - including major accounts like Aramco, ADNOC, KOC, SLB, and Baker Hughes (BKR). Built to give leadership a fast performance-vs-budget read and give account managers a customer-by-product-line drill-down for the same data.

### Business Objective
Finance and sales leadership needed a single view to answer:
- Are we tracking to our annual revenue and gross profit budget — and by how much?
- Which customers and product lines are ahead of plan, and which are falling behind?
- Is our profit margin holding up, or is COGS/freight eating into it faster than planned?

### Dashboard Preview

**Executive View** - revenue/GP-vs-budget scorecard, top customers, quarterly and monthly trends
<p align="center">
  <img src="https://raw.githubusercontent.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/main/2.%20Global%20Customer%20Lens/Executive%20View.png" width="90%" alt="Global Customer Lens - Executive View">
</p>

**Operational View** - customer × product-line drill-down with variance analysis and Top 10/20/25 filtering
<p align="center">
  <img src="https://raw.githubusercontent.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/main/2.%20Global%20Customer%20Lens/Operational%20View.png" width="90%" alt="Global Customer Lens - Operational View">
</p>

> 🔍 [View Executive Screenshot full-size](https://github.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/blob/main/2.%20Global%20Customer%20Lens/Executive%20View.png) · [View Operational Screenshot full-size](https://github.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/blob/main/2.%20Global%20Customer%20Lens/Operational%20View.png)

### Key Insights Surfaced
- Q1 actuals landed at **₹47.75M revenue** against a **₹199.17M** full-year budget - ~24% of annual target reached, just under the 25% quarterly pace needed to stay on track
- **Gross margin is compressing**: actual GP margin sits at **~40.8%** (₹19.46M / ₹47.75M) versus a **~43.4%** budgeted margin — revenue is close to pace, but profitability is trailing it
- **Aramco** is both the top revenue account (₹9.1M) and tracking closest to its individual target (~30% attainment), while **SLB and BKR** are visibly behind their budgeted pace - flagging them as at-risk accounts for account management follow-up
- **PCE and RC** are the strongest gross-profit-contributing product lines; **PDC and Completion** are lagging toward their GP budgets
- Built a **Top 10 / Top 20 / Top 25 dynamic filter** on the operational table so account managers can instantly narrow from the full customer base to their priority accounts without manual filtering

### Tools & Techniques Used
- **Power BI Desktop** - data modeling, report design
- **Power Query** - data cleaning and shaping
- **DAX** - Actual vs. Budget variance measures, GP% and margin calculations, dynamic Top N filtering logic
- **Data modeling** - customer, product line, and time dimension relationships
- Conditional formatting on variance columns for at-a-glance over/under-budget signals

### What This Project Demonstrates
- **Actual-vs-budget variance analysis** - a core FP&A/sales-ops skill beyond simple sales reporting
- Designing a **drill-through path** from executive KPIs down to customer × product-line granularity
- Using **dynamic parameters (Top N filtering)** to make a dense table usable for different audiences
- Reading profitability, not just revenue - flagging margin compression as a distinct signal from revenue growth
