# California CalFresh Coverage Gap & Economic Distress Analysis

## Project Overview
As a data analyst passionate about social equity and public policy, I built this end-to-end analytics project to investigate where public assistance programs are falling short. Using official data from the **U.S. Census Bureau's 2024 American Community Survey (ACS) Table S2201** (Food Stamps/SNAP dynamics), this project evaluates county-level economic distress across California and highlights administrative blind spots where high poverty levels contrast sharply with low program enrollment.

The primary goal was to build a fully reproducible pipeline that uncovers why certain rural mountain and agricultural communities experience severe coverage gaps despite acute economic need.

---

## Repository Structure

The repository is organized into distinct directory tiers to ensure complete transparency, reproducibility, and clean data provenance:

* **`/data-raw/`**
  * Contains the original, unaltered U.S. Census Bureau CSV dataset (`ACSST1Y2024.S2201-Data.csv`) straight from the source to maintain absolute data integrity.
* **`/data-processed/`**
  * Houses the cleaned, standardized spreadsheet model (`SNAP_California_Fixed.xlsx`) complete with custom calculation formulas deriving poverty-to-participation ratios and coverage gap metrics.
* **`/visualizations/`**
  * Features high-resolution exploratory outputs, including:
    * `top_10_coverage_gaps_chart.png`: Horizontal ranking charts spotlighting the counties experiencing the most severe participation deficits.
    * `quadrant_scatter_plot.png`: Exploratory scatter plots mapping economic vulnerability against safety net uptake.

---

## Analytical Methodology & Workflow

1. **Data Ingestion & Hygiene:** Ingested raw ACS demographic and economic tables, handling structural headers, missing values, and data type formatting.
2. **Metric Engineering:** Developed custom calculation models to isolate county-level poverty thresholds and compare them directly against active CalFresh uptake rates.
3. **Exploratory Data Analysis (EDA) & Visualization:** Generated targeted charts to identify outliers, clustering patterns, and systemic administrative hurdles in agricultural and rural regions.

---

## Key Insights & Findings
* **Rural Disparities:** Several agricultural and mountain counties exhibit high household poverty rates paired with disproportionately low CalFresh participation, indicating systemic barriers to program access.
* **Administrative Blind Spots:** Standardizing the gap metrics clearly separates counties effectively reaching vulnerable populations from those requiring targeted outreach and policy intervention.

---

## Policy & Business Recommendations for Agencies

Based on the empirical findings of this coverage gap analysis, county human services agencies and policymakers can drive data-backed operational decisions across four key areas:

1. **Targeted Outreach & Mobile Infrastructure:** Deploy mobile enrollment units and partner with rural health clinics and community-based organizations (CBOs) directly within identified high-gap zip codes.
2. **Streamlined Intake & Cross-Enrollment:** Reduce administrative friction by reviewing county application drop-off rates, simplifying recertification paperwork, and leveraging existing data from programs like Medi-Cal to fast-track eligible households.
3. **Transportation & Retail Access Planning:** Use spatial participation insights to route public transit toward grocery access points and direct funding toward EBT equipment and matching programs at farmers' markets.
4. **Data-Driven Legislative Advocacy:** Equip state and local decision-makers with county-level performance benchmarks to design targeted safety net protections and ensure equitable resource distribution.

---

## Tools & Frameworks
* **Spreadsheet Modeling & Data Cleaning:** Microsoft Excel (Advanced formulas, data structuring, and transformation pipelines).
* **Data Sources:** U.S. Census Bureau (ACS 1-Year Estimates, Table S2201).
* **Methodological Standards:** Built following rigorous civic data analysis frameworks (BroadStreet Institute principles).

---
*Created by [Enigma Valdez](https://github.com/EnigmaValdez).*
