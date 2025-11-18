 
# Business Insights 360 — Power BI Dashboard (AtliQ Hardware)

**End-to-end Power BI project** delivering Finance, Sales, Marketing, Supply Chain and Executive dashboards for a consumer-electronics company.

---

## Overview
This project demonstrates a full analytics pipeline:
- Data ingestion & cleansing (Power Query)
- Star-schema modeling
- Advanced DAX for P&L, LY, YoY, Forecast Accuracy
- Interactive dashboards with slicers, buttons, and drill-through

---

## Pages & Key Insights

### Home Page

<img width="1504" height="891" alt="image" src="https://github.com/user-attachments/assets/bcb9ccfa-55ee-41b3-8037-072b9a2f6d82" />

- Navigation hub for stakeholders; includes refresh info and doc links.

---

### Finance View

<img width="1579" height="908" alt="image" src="https://github.com/user-attachments/assets/d588ed6f-10aa-4df4-8f18-ce1f9ab3c91b" />

- **P&L matrix** (dynamic rows via SWITCH)
- LY / YoY / BM comparisons
- Net Sales, Gross Margin %, Net Profit %
- Trend chart and top/bottom customer product insights

---

### Sales View

<img width="1574" height="890" alt="image" src="https://github.com/user-attachments/assets/8926d3ef-2e60-41f1-a7d9-3d053f5ad55e" />


- Top customers and product performance
- Performance matrix (Net Sales vs Gross Margin)
- Unit economics and revenue decomposition

---

### Marketing View

<img width="1558" height="876" alt="image" src="https://github.com/user-attachments/assets/b853f6ad-0725-42c9-8ae2-574705c019fc" />


- Product & market profitability (GM% vs Net Sales)
- Unit economics and YoY product performance

---

### Supply Chain View

<img width="1600" height="883" alt="image" src="https://github.com/user-attachments/assets/6ed1d1dd-3814-4254-8c9a-5ac8eb737fbc" />

- Forecast Accuracy, Net Error, ABS Error
- Risk tagging: Out-of-Stock / Excess Inventory
- Trend charts and top/bottom product/customer accuracy

---

### Executive View

<img width="1573" height="890" alt="image" src="https://github.com/user-attachments/assets/1b064028-a5ca-49cc-a122-621df27a004b" />

- Consolidated KPIs for leadership
- Revenue by division/channel
- Top customers & products snapshot

---

## Key Technical Notes
- DAX highlights: `CALCULATE`, `SWITCH`, `ALLNOBLANKROW`, `UNION`, `SAMEPERIODLASTYEAR`, `SUMX`, `DISTINCT`
- Data model uses a Star Schema (fact tables + dims)
---


