E-commerce Sales & Returns Dashboard
Live: https://mrjayvirtual.github.io/Ecommerce-Returns-Dashboard/
The problem
Revenue dashboards alone hide a real cost center: returns. A category can look like a top performer on revenue while quietly bleeding margin through return rate. This dashboard puts both numbers side by side so a decision-maker doesn't optimize for the wrong metric.
What it does
An interactive dashboard filtered by region, showing:
Total revenue, units sold, average order value
Return rate with a color-coded health signal (green/amber/red)
Revenue by month and by category
Process
Modeled order-level data: category, region, revenue, units, returns, month
Built reusable aggregation helpers (not hardcoded per chart — same function powers every grouping)
Derived business metrics: AOV and return rate, both requiring division across aggregated sums
Added conditional formatting so a raw number becomes an instant decision signal
Stack
React, inline component state, sample data.
Note
Built with sample/synthetic data for demonstration — the generic "any business's numbers" proof piece in this set, intentionally not tied to one brand.
