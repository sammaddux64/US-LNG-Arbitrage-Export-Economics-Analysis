# US LNG Arbitrage & Export Economics Analysis

## Overview
This project analyzes the economic drivers of U.S. LNG exports by evaluating global natural gas
price differentials, delivered LNG netbacks, and arbitrage margins relative to Henry Hub.
The goal is to assess when LNG exports are economically viable and whether export volumes
respond to arbitrage signals.

---

## Key Questions
- How do global natural gas prices compare to Henry Hub over time?
- When are LNG exports economically viable after accounting for costs?
- Do higher arbitrage margins correspond to increased U.S. LNG export volumes?

---

## Data Sources
- **U.S. Energy Information Administration (EIA)**
  - Henry Hub natural gas prices
  - U.S. LNG export volumes
- **European gas price proxy** (TTF-based)
- **Asia LNG price proxy** (JKM-based)

---

## Methodology
- Built a **star-schema data model** in Power BI using a centralized Date table
- Calculated **delivered LNG netbacks** by destination using assumed:
  - Liquefaction costs
  - Shipping costs
  - Regasification costs
- Derived **arbitrage margins** as delivered netback minus Henry Hub
- Validated economic signals against observed U.S. LNG export volumes

---

## Key Insights
- Europe and Asia gas prices generally trade above Henry Hub, creating
  structural LNG arbitrage potential.
- Arbitrage margins expanded significantly during the 2021–2022 global supply shocks.
- U.S. LNG exports increase during sustained positive arbitrage periods but
  plateau at liquefaction capacity limits.
- Short-term margin volatility does not immediately translate to export changes,
  reflecting long-term contracts and operational constraints.

---

## Tools & Skills
- Power BI (data modeling, DAX, visualization)
- DAX (netbacks, arbitrage margins, time-aware KPIs)
- Energy market analysis
- Data storytelling & dashboard design

---

## How to View
- Download the **PDF** for a static overview of the analysis
- Open the **PBIX** file in Power BI Desktop to explore the interactive model
