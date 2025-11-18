## Fact Tables
- fact_actuals_estimates
  
  - DateKey, ProductID, CustomerID, GrossSales, NetSales, Qty, ManufacturingCost, FreightCost 

## Dimension Tables

- dim_date (Date, FiscalYear, Quarter, Month, fy_desc)
- dim_product (ProductID, Category, Segment)
- dim_customer (CustomerID, Region, Market)

## Key Measures (DAX)
- GS $ = SUM(fact_actuals_estimates[GrossSales])
- NS $ = SUM(fact_actuals_estimates[NetSales])
- P & L values = <SWITCH-based master measure> (see notes/video_script.md)
- P & L LY = CALCULATE([P & L values], SAMEPERIODLASTYEAR('dim_date'[Date]))
- Forecast Accuracy = 1 - (ABS Error / Sales Qty)

<img width="975" height="644" alt="image" src="https://github.com/user-attachments/assets/799b75f8-6a82-4bb7-99eb-35cda2ee8168" />
