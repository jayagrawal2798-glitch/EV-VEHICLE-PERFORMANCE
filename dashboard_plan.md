# Tableau Dashboard Plan

## 1. Executive Overview
**Purpose:** Provide a fast summary of the sample dataset.

**KPI cards:** Total annual sales (sum), average driving range, average battery capacity, average customer rating. Label these as sample-data metrics.

**Views:**
- Line chart: annual sales by year.
- Bar chart: sales by manufacturer (sort descending; show top 10).
- Stacked bar: sales by vehicle segment and year.
- Detail table: manufacturer, segment, range, capacity, rating.

**Filters:** Year, country, manufacturer, segment, chemistry.

## 2. Manufacturer Performance
- Horizontal bar: annual sales by manufacturer.
- Dot plot: market share by manufacturer.
- Scatter plot: average range vs. battery capacity, sized by sales and colored by segment.
- Use a year filter and manufacturer highlight action.

## 3. Battery & Technology
- Box plot or bar chart: range by chemistry.
- Scatter plot: battery capacity vs. range.
- Bar chart: average charging minutes by chemistry.
- Table: chemistry, capacity, range, charging time.
- Clearly note that the values are synthetic and charging conditions are not standardized.

## 4. Geography & Customer Insights
- Bar chart: sales by manufacturing country.
- Heatmap: country by vehicle segment.
- Scatter plot: customer rating vs. range.
- Filters: country, segment, year.

## Design guidance
- Canvas: white or light gray.
- Accent: teal; reserve one secondary color for highlights.
- Use consistent units (km, kWh, minutes, percent).
- Keep titles descriptive, avoid 3D charts, and show the data period.
- Add a visible note: **Synthetic demonstration data — not official market statistics.**

## Quality checks
1. Verify field data types and nulls.
2. Check that all chart axes start at meaningful values.
3. Confirm filters affect every intended view.
4. Avoid summing customer ratings or range across records; use averages where appropriate.
5. Validate market-share denominators before using real data.
