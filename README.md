# ✈️ Aviation Safety Analysis (2010–2023)

## Overview

This project analyzes aviation accident data from the NTSB to identify low-risk aircraft types for a company expanding into commercial and private aviation.

## Business Understanding

The company aims to purchase aircraft but lacks domain-specific safety insights. This analysis helps decision-makers understand which aircraft present the lowest operational risk.

## Data Understanding and Analysis
    **Data Source:**  
    [NTSB Aviation Accident Dataset](https://www.ntsb.gov/)  
    Filtered from 1962–2023 to only 2010–2023 civil airplane accidents in the U.S.

    **Key Columns Used:**
    - `event_date`, `make`, `model`, `injury_severity`
    - `total_fatal_injuries`, `total_uninjured`, `aircraft_category`
    - Derived: `aircraft` = Make + Model

    **Data Cleaning & Imputation:**
    - Filtered for airplanes (not helicopters, balloons, etc.)
    - Standardized column names
    - Imputed numerical columns with medians
    - Categorical columns filled with "Unknown"

    **Analysis Metrics:**
    - Total accident count
    - Total injuries & fatality rate
    - Average number of uninjured passengers
    Three visualizations (the same visualizations presented in the slides and notebook)
## Conclusion
    Summary of conclusions including three relevant findings
    