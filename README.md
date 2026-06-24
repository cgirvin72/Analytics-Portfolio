# Vendor Consolidation Analysis — Interactive Dashboard

A Power BI-styled interactive dashboard analyzing a synthetic enterprise vendor consolidation program across Finance, Risk, and Operations departments.

**Live demo:** _(add your deployed Vercel URL here once live)_

## What this is

This dashboard is one piece of a three-part portfolio project demonstrating financial modeling and BI capability:

1. **Excel model** — scenario-driven vendor consolidation analysis (Conservative / Base / Aggressive), 823 formula-driven cells, multi-year ROI and break-even logic
2. **This dashboard** — the same dataset, rebuilt as an interactive cross-filtering experience: department slicers, a variance heatmap matrix, scenario comparison, and drill-through detail
3. **DAX/data model reference** — documents how this dashboard's logic maps to a real Power BI data model (star schema, DAX measures), so the approach is reproducible directly in Power BI Desktop

## Why three formats for one dataset

Each tool is used for what it's actually good at:

- **Excel** — when the audience needs to change assumptions and see formulas recalculate live
- **This HTML dashboard** — when the audience wants to click through and explore, the way they would in a real Power BI report
- **The DAX reference doc** — proof of the technical modeling underneath, for anyone who wants to see how this would be built natively in Power BI

## Data

All figures are synthetic and built for demonstration purposes. No real employer, client, or proprietary data is used anywhere in this project.

## Pages

- **Executive Overview** — top-line KPIs and department-level savings, with a department slicer that cross-filters every visual on the page
- **Variance Deep-Dive** — a conditional-formatted heatmap of variance % across department × cost category × month
- **Scenario Comparison** — toggle between three consolidation scenarios (A/B/C) to compare ROI, break-even, and net savings
- **Drill-Through Detail** — click any bar, table row, or heatmap cell to land here with full monthly trend detail for that selection

## Tech

Single self-contained HTML file. No build step, no dependencies — open `index.html` directly or deploy as a static site.

---

Built by Christopher S. Girvin — [LinkedIn] · [email]
