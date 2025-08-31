# Project: The Great Displacement
## State Collapse and Population Restructuring in Post-Coup Myanmar (2019 vs. 2024)

**Author:** Nyein Pyae Sone
**Institute:** Myanmar Conflict Analysis Research Institute (MCARI)
**Date:** August 2024
**Status:** Complete

---

### **1. Executive Summary**

This repository contains the data and analysis for "The Great Displacement," an analytical brief examining the collapse of state administration in post-coup Myanmar. 
The project leverages the SAC's October 2024 census data, not as a demographic tool, but as a direct proxy for state control.

The analysis reveals a "governance gap" of **18.9 million people**—individuals the state was unable to enumerate. 
With a national average census coverage of only **54%**, the data provides empirical proof that state functions have collapsed in nearly half the country. 
The core finding is a story of two parallel dynamics: a catastrophic **collapse of governance in rural areas** 
(e.g., 6% coverage in rural Sagaing) and a simultaneous **consolidation of population in urban strongholds** (e.g., 130% urban coverage in Naypyitaw).

The primary conclusion is that the conflict has not just displaced people, but has fundamentally **displaced governance itself.**

---

### **2. The Final Product**

The complete findings are presented in an interactive data dashboard and a formal analytical brief.

*   **View the Interactive Dashboard:** [https://tinyurl.com/thegreatdisplacementmyanmar24]
*   **Read the Full Analytical Brief (PDF):**
    *   [English Version](https://github.com/Nyein-V/myanmar-map-data/blob/main/The%20Great%20Displacement%20(1).pdf)
    *   [Myanmar Version](https://github.com/Nyein-V/myanmar-map-data/raw/main/The%20Great%20Displacement%20(Burmese%20Version)%20(1).pdf)

![Dashboard Screenshot](https://github.com/Nyein-V/myanmar-map-data/raw/main/final_dashboard_aug25.png)

---

### 3. Methodology & Process

This analysis was conducted at the **State/Region level** following an initial exploratory phase at the township level. 
The strategic pivot to a higher level of aggregation was made to ensure analytical integrity due to the unavailability of a reliable township-level baseline for the 2019 data.


*   **Baseline Data:** 2019 Inter-Censal Survey (State/Region level).
*   **Post-Coup Data:** SAC-collected enumerated population data from October 2024 (Township level, aggregated to State/Region).

**Core Metric:**
*   The **"Census Coverage Ratio"** (`2024 Enumerated Population / 2019 Baseline Population`) was used as the primary proxy for state control and administrative reach.

**Analytical Process:**
1.  **Data Cleaning & Preparation:** Raw data from multiple sources was cleaned, unified, and aggregated into a single master dataset at the State/Region level.
2.  New metrics, such as the Urban/Rural Coverage Ratios, were calculated.
3.  **Strategic Analysis:** Key findings were identified by comparing census coverage across different geographic and demographic segments (Total, Urban vs. Rural).
4.  **Visualization & Dashboarding:** The final analysis was presented in an interactive dashboard to visualize the core findings.

**Tools Used:**
*   **Data Processing:** Google Sheets
*   **Data Visualization:** Looker Studio
*   **Geospatial Processing:** Mapshaper.org (for initial GeoJSON conversion)
---

### **4. Data Files in this Repository**

*   `final_state_region_analysis.csv`: The final, cleaned master dataset used for the analysis.
*   `mmr_polbnda_adm3_250k_mimu_20240215.json`: The GeoJSON boundary file for Myanmar townships (Note: This was used in an earlier, exploratory phase of the analysis before the final pivot to State/Region level).
*   `The_Great_Displacement_Brief_EN.pdf`: The final analytical report in English.
*   `The_Great_Displacement_Brief_MM.pdf`: The final analytical report in Myanmar language.

---
