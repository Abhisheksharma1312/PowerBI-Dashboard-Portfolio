## Revenue Report

### Overview
A two-view Power BI dashboard tracking actual vs. budgeted revenue across regions, countries, and product lines for a multi-year (2020–2025) revenue reporting cycle. Built to give leadership a fast attainment read and give finance a period-by-period, country-level drill-down for variance investigation.

### Business Objective
Finance leadership needed a single view to answer:
- How is actual revenue tracking against the FY2025 budget, and by how much are we falling short or ahead?
- Which regions and product lines are driving - or dragging down - overall attainment?
- Where exactly (which country, which period) is the biggest variance showing up, so it can be investigated?

### Dashboard Preview

**Executive View** - revenue-vs-budget trend, top regions, and product-line breakdown
<p align="center">
  <img src="https://raw.githubusercontent.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/main/3.%20Revenue%20report/Revenue%20Dashboard.png" width="90%" alt="Revenue Report - Executive View">
</p>

**Operational View** - region × country × period variance table with conditional formatting
<p align="center">
  <img src="https://raw.githubusercontent.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/main/3.%20Revenue%20report/Revenue%20Operational%20View.png" width="90%" alt="Revenue Report - Operational View">
</p>

> 🔍 [View Executive Screenshot full-size](https://github.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/blob/main/3.%20Revenue%20report/Revenue%20Dashboard.png) · [View Operational Screenshot full-size](https://github.com/Abhisheksharma1312/PowerBI-Dashboard-Portfolio/blob/main/3.%20Revenue%20report/Revenue%20Operational%20View.png)

### Key Insights Surfaced
- FY2025 actual revenue is tracking at roughly **11% of budget** (~$661K actual vs. ~$5.94M budgeted) - a material shortfall surfaced right at the top-level KPI cards
- **Africa** is both the largest budgeted region (**$4.0M**) and the largest actual-revenue contributor (**$0.35M**) - but even the top region is attaining under 10% of its target, showing the shortfall is broad-based rather than isolated to one market
- **EHO DHP** is the dominant product line by budget (**$5.7M**) yet shows only **$0.6M** in actual revenue, mirroring the region-level gap and pointing to a product-line-wide issue rather than a regional one
- Built a **Region → Country → Period drill-down table** with color-coded variance (red/green) that lets finance move from the headline shortfall straight to the specific country and period driving it - e.g., Egypt shows a meaningful negative variance across multiple periods
- Multi-year trend view (2020-2025) gives leadership historical context for whether FY2025's gap is a one-off dip or part of a longer pattern

### Tools & Techniques Used
- **Power BI Desktop** - data modeling, report design
- **Power Query** - data cleaning and shaping
- **DAX** - Actual vs. Budget variance measures across region, country, product line, and period
- Conditional formatting on variance columns for at-a-glance over/under-budget signals
- Multi-level slicers (Region, Country, Period, Fiscal Year, Product View) with cross-report navigation

### What This Project Demonstrates
- **Budget-attainment analysis at scale** - rolling up a large shortfall to the exact region/country/period causing it
- Designing a **geographic + time-period drill-down** (not just a flat customer table like Project 2)
- Communicating a **negative finding clearly** - the dashboard doesn't hide the shortfall, it's built to surface and explain it
