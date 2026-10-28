# Suggested Tableau Calculated Fields

Create these only after checking the grain of your data. The supplied dataset is synthetic.

## Average Driving Range
```tableau
AVG([Driving_Range_km])
```

## Average Battery Capacity
```tableau
AVG([Battery_Capacity_kWh])
```

## Average Customer Rating
```tableau
AVG([Customer_Rating])
```

## Average Fast-Charging Duration
```tableau
AVG([DC_Fast_Charge_Min])
```

## Sales in Thousands
```tableau
SUM([Annual_Sales_Units]) / 1000
```
Format with one decimal place and label as thousands of sample units.

## Range Efficiency Proxy (km per kWh)
```tableau
IF AVG([Battery_Capacity_kWh]) > 0 THEN
    AVG([Driving_Range_km]) / AVG([Battery_Capacity_kWh])
END
```
This is only a simple range-to-capacity proxy, not a standardized efficiency rating.

## Year-over-Year Sales Change
Use a view with `YEAR([Year])` and `SUM([Annual_Sales_Units])`, then apply **Quick Table Calculation → Percent Difference** with previous year as the relative base. Ensure the table calculation addresses Year.

## Important note
Do not sum `Market_Share_Percent` across manufacturers or years unless the data model and denominator make that aggregation meaningful. The sample values are illustrative only.
