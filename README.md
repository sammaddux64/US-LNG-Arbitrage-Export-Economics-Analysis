# US-LNG-Arbitrage-Export-Economics-Analysis
This project analyzes the economic drivers of U.S. LNG exports by evaluating global natural gas price differentials, delivered netbacks, and arbitrage margins relative to Henry Hub. The goal is to assess when LNG exports are economically viable and whether export volumes respond to arbitrage signals.
- How do global gas prices compare to Henry Hub over time?
- When are LNG exports economically viable after costs?
- Do higher arbitrage margins correspond to increased U.S. LNG exports?
- U.S. Energy Information Administration (EIA)
  - Henry Hub natural gas prices
  - U.S. LNG export volumes
- European gas price proxy (TTF-based)
- Asia LNG price proxy (JKM-based)
- Built a star-schema data model in Power BI using a centralized Date table
- Calculated delivered LNG netbacks by destination using assumed:
  - Liquefaction costs
  - Shipping costs
  - Regasification costs
- Derived arbitrage margins as netback minus Henry Hub
- Validated economic signals against observed LNG export volumes
- Europe and Asia gas prices generally trade above Henry Hub, creating
  structural LNG arbitrage potential.
- Arbitrage margins expanded significantly during 2021–2022 supply shocks.
- U.S. LNG exports increase during sustained positive arbitrage periods but
  plateau at liquefaction capacity limits.
- Short-term margin volatility does not immediately translate to export changes,
  reflecting long-term contracts and operational constraints.
- Power BI (data modeling, DAX, visualization)
- DAX (netbacks, arbitrage margins, time-aware KPIs)
- Energy market analysis
- Data storytelling & dashboard design
- Download the PDF for a static overview
- Open the PBIX file in Power BI Desktop to explore the interactive model
