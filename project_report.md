# EV Market Analysis — Project Report

## 1. Introduction
This project demonstrates how a Tableau dashboard can organize electric-vehicle market indicators into a consistent, interactive view for exploratory analysis.

## 2. Objectives
- Compare manufacturers and vehicle segments.
- Explore trends in illustrative annual sales.
- Examine the relationship between battery capacity and driving range.
- Compare battery chemistry categories and charging duration.
- Include customer-rating and sustainability-style indicators for dashboard prototyping.

## 3. Data
The repository includes 80 synthetic demonstration records spanning 2021–2025. Fields include manufacturer, manufacturing country, segment, chemistry, battery capacity, range, charging duration, annual sales, market share, rating, and sustainability score. These values are generated for demonstration and are not official market data.

## 4. Methodology
1. Load the CSV into Tableau.
2. Validate column types and units.
3. Build KPI cards and manufacturer/year comparisons.
4. Use filters for year, manufacturer, country, segment, and chemistry.
5. Compare battery capacity and range with scatter plots.
6. Review dashboard labels, scales, and interactivity.

## 5. Suggested analysis questions
- Which manufacturers have the highest illustrative sales in each year?
- How do range and battery capacity vary by segment?
- Which chemistry categories show different average range or charging duration in this sample?
- Are ratings associated with range in the demonstration data?

## 6. Limitations
The data is synthetic and has not been validated against public reports. Sales, market share, range, ratings, and sustainability scores must not be interpreted as real manufacturer performance. Charging times vary with vehicle, charger power, temperature, state of charge, and test protocol. Country labels indicate an associated manufacturer country, not verified production origin.

## 7. Next steps
- Replace the sample data with a trusted source and document its provenance.
- Normalize sales data by region and year if making market-share comparisons.
- Define a transparent sustainability methodology.
- Build and test the Tableau workbook, then publish the `.twbx` or a Tableau Public link.

## 8. Conclusion
This repository provides a starter dataset and documented plan for a clean, detail-oriented EV market dashboard. Validated conclusions require verified source data and a completed Tableau workbook.
