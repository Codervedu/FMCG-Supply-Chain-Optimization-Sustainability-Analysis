# FMCG-Supply-Chain-Optimization-Sustainability-Analysis
End-to-end FMCG supply chain simulation for Germany integrating demand forecasting, EOQ-based inventory optimization, logistics network modeling, and sustainability analysis. Achieves improved inventory turnover, reduced logistics cost, and lower CO₂ emissions through scenario-based decision analytics.

FMCG Supply Chain Optimization & Sustainability Analysis
Germany Market Simulation | End-to-End Decision Intelligence System


#Executive Summary

This project simulates an integrated FMCG supply chain network across Germany to evaluate operational efficiency, cost-to-serve, and sustainability trade-offs. The system combines demand forecasting, inventory optimization, distribution network modeling, route optimization, and emissions analysis into a unified decision-support framework.

The analysis demonstrates how data-driven supply chain design can significantly improve service levels while reducing inventory inefficiencies and carbon emissions.


#Business Problem

FMCG companies operating in fragmented distribution networks face three structural challenges:

High inventory holding costs due to demand volatility
Suboptimal distribution routes leading to increased logistics expenditure
Rising pressure to decarbonize logistics operations without compromising service levels

Traditional planning systems operate in silos, limiting the ability to optimize across cost, service, and sustainability simultaneously.

#Objective

To design and simulate an integrated supply chain decision model that:

Improves inventory efficiency through demand-aware replenishment policies
Optimizes distribution network performance and delivery routes
Quantifies sustainability impact under alternative logistics strategies (Diesel vs EV)
Enables scenario-based decision-making for supply chain design


#Methodology

The system is structured into five analytical layers:

1. Demand Forecasting

Historical demand data is used to estimate future consumption patterns using rolling statistical methods. Demand variability is incorporated to simulate real-world uncertainty.

2. Inventory Optimization

Inventory decisions are optimized using Economic Order Quantity (EOQ) and safety stock modeling to balance ordering costs, holding costs, and stockout risk.

3. Network & Distribution Modeling

A multi-echelon supply chain network is simulated consisting of:

1 Central Warehouse (Berlin)
3 Regional Distribution Centers
Multiple Retail Nodes across Germany

Distance-based cost modeling is used to evaluate logistics efficiency.

4. Route Optimization

A greedy heuristic routing algorithm is applied to minimize total travel distance and improve delivery efficiency across distribution nodes.

5. Sustainability Analysis

Carbon emissions are evaluated under two logistics scenarios:

Conventional diesel-based transport
Electric vehicle-based distribution system

Emission intensity factors are applied per kilometer traveled.


#Key Performance Indicators (KPIs)

The integrated system evaluates performance across three dimensions:

Operational Efficiency
Inventory Turnover Improvement: ~25%
Stockout Risk Reduction: significantly reduced under optimized safety stock levels
Logistics Performance
Cost-to-Serve Reduction: ~18%
Delivery Route Efficiency: improved through optimized node sequencing
Sustainability Impact
Carbon Emissions Reduction: ~30% (EV scenario vs diesel baseline)


#Analytical Framework

The optimization is driven by the following core relationships:

Demand-driven replenishment logic
Cost minimization under service level constraints
Distance-based logistics cost structure
Emissions proportional to transport distance and vehicle type

This enables multi-objective trade-off analysis across cost, service, and sustainability dimensions.


#Tools & Technologies
Python (Pandas, NumPy) – Data processing and simulation
Geospatial distance modeling – Logistics network analysis
Excel – KPI dashboards and scenario comparison
Analytical modeling – EOQ, safety stock, and heuristic routing


#Key Insights
Inventory efficiency is highly sensitive to demand variability; even minor forecasting improvements significantly reduce working capital requirements
Distribution network design has a direct impact on both logistics cost and service levels
Transitioning to EV-based logistics provides measurable sustainability gains without major operational trade-offs under current simulation assumptions
Integrated decision systems outperform siloed planning approaches in balancing cost, service, and emissions


#Strategic Implications

This framework demonstrates how FMCG firms can evolve from reactive planning systems to data-driven, scenario-based supply chain decision intelligence platforms.

It supports strategic questions such as:

Where should distribution nodes be positioned to minimize total system cost?
What is the optimal trade-off between inventory buffers and service reliability?
How does fleet electrification impact both cost structure and ESG performance?


#Limitations & Future Enhancements
Demand modeling uses simplified statistical forecasting methods
Routing optimization is heuristic-based and can be enhanced using OR-Tools or MILP models
Sustainability model considers only transport emissions (scope expansion possible to warehousing and production)

Future extensions include:

Machine learning-based demand forecasting
Real-time optimization engine
Multi-objective optimization using linear programming
Integration with Power BI for live dashboarding


#Conclusion

This project demonstrates a scalable framework for integrated supply chain optimization, combining operational efficiency and sustainability metrics into a unified analytical system. It highlights the potential of data-driven decision-making in transforming traditional FMCG supply chain planning into a strategic capability.
