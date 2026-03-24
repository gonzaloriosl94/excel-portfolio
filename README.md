# Excel & Data Strategy Portfolio: Revenue Management System

## Project Overview
This repository showcases a high-impact **Automated Pricing Engine** designed to recover and stabilize profit margins for a large-scale e-commerce operation (Shopify). 

The system transitioned the company from fragmented, local data silos (PDF/Word/Excel) into a centralized, cloud-based **Revenue Management Infrastructure**.

## Key Features & Data Architecture
The core of this project is a relational logic engine that processes thousands of SKUs based on dynamic variables:

* **ETL Pipeline:** Automated extraction and normalization of supplier data (Costs, MAP, MSRP) from multiple formats into a Master SKU Database.
* **Tiered Margin Matrix:** A sophisticated "Sliding Scale" logic that adjusts margins based on price points to optimize dollar-margin contribution.
* **The Strategy Trigger:** A selection-based model allowing for real-time pricing pivots:
    1. **Manual Override Price:** Tactical overrides.
    2. **Margin-Optimized Price:** Margin-matrix driven.
    3. **Category Discount Price:** Brand/Division-wide discounts.
    4. **MAP / MRP Compliance Price:** Hard-coded MAP/MRP protection.
* **Competitor Intelligence:** A benchmarking module monitoring 15+ competitors to ensure market relevance without sacrificing the floor margin.

## Technical Skills Demonstrated
* **Advanced Logic:** Nested XLOOKUP, INDEX-MATCH, IFS, ARRAYFORMULA, and complex conditional formatting.
* **Data Modeling:** Relational database structure within spreadsheets (Master Tables, Dimension Tables, and Fact Tables).
* **Process Automation:** Reduction of manual pricing updates through automated freight, tariff, and tax calculations.
* **Business Intelligence:** Turning raw cost data into actionable pricing strategies.

## Repository Structure
* /Documentation: Detailed breakdown of the 4 pricing strategies.
* /Templates: (Optional) Anonymized version of the calculator logic.
* /Visuals: Screenshots of the Pricing Model interface and Margin Curves.
---
**Note:** All sensitive company data, supplier names, and specific pricing figures have been anonymized or blurred to protect proprietary information.
