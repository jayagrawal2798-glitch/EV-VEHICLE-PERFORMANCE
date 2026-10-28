# EV Market Analysis — Tableau

A portfolio project exploring electric-vehicle (EV) market patterns through a Tableau-ready sample dataset and dashboard documentation.

> **Data note:** `data/ev_market_data.csv` is synthetic sample data created for demonstration and dashboard development. It is not official market data and should not be cited as real-world sales or market share.

## Project objectives
- Compare EV manufacturers and vehicle segments.
- Explore annual sales, market share, range, battery capacity, charging time, and customer ratings.
- Compare battery chemistries and manufacturing regions.
- Prepare a clear, filterable Tableau dashboard for market exploration.

## Repository contents
- `data/ev_market_data.csv` — sample EV market dataset.
- `data/data_dictionary.csv` — field definitions and units.
- `tableau/dashboard_plan.md` — recommended dashboard layout and interactions.
- `tableau/calculated_fields.md` — suggested Tableau calculations.
- `docs/project_report.md` — project scope, method, limitations, and next steps.
- `.gitignore` — common local and Tableau temporary files.
- `LICENSE` — MIT License.

## Recommended dashboards
1. **Executive Overview:** total sample sales, average range, average rating, sales by year, and segment mix.
2. **Manufacturer Performance:** sales and market-share comparisons by manufacturer.
3. **Battery & Technology:** battery chemistry, capacity, range, and charging time.
4. **Geography & Customer Insights:** manufacturing country, segment, and customer rating.

## Use in Tableau
1. Download or clone this repository.
2. In Tableau Desktop, select **Connect → Text File** and open `data/ev_market_data.csv`.
3. Confirm data types using `data/data_dictionary.csv`.
4. Build the views described in `tableau/dashboard_plan.md`.
5. Use the formulas in `tableau/calculated_fields.md` as a starting point.
6. Replace the synthetic dataset with a trusted, documented source before making factual market claims.

## Suggested visual style
Use a white or light-gray canvas, dark charcoal text, and teal accents. Keep KPI cards restrained, use consistent units, label charts directly where practical, and place filters in a compact side panel.

## Tools
- Tableau Desktop / Tableau Public
- CSV data
- Markdown documentation

## Author
Advait Pratap Singh

## Limitations
This repository currently contains a Tableau-ready dataset and project documentation, not a packaged Tableau workbook (`.twbx`). The sample values are synthetic. Add a workbook after building and validating the dashboards in Tableau.
