# CO2 emissions analysis: Germany

**Student:** Erica Joyce Lagahit Descartin  
**Country / ISO-3:** Germany / DEU  
**Study period:** 1990 to 2024  
**Declared to instructor on:** [11/07/26]  

## Research question
How have annual CO₂ emissions and per-capita emissions changed in Germany between 1990 and 2024?

## Data source and definitions
* **Source:** Our World in Data (OWID) CO₂ and Greenhouse Gas Emissions dataset.
* **Dataset URL:** https://github.com/owid/co2-data
* **Downloaded on:** [Insert Download Date][cite: 2]. Selected columns: `year`, `co2`, `co2_per_capita`.
* **Units:** `co2` is reported in million tonnes per year; `co2_per_capita` is reported in tonnes per person per year.

## How to reproduce the analysis
1. Install R, RStudio, and Git. Open this repository as an RStudio Project.
2. Ensure an active internet connection is available for the initial full CSV download.
3. In the RStudio Console, run:
   ```r
   source("scripts/analyze_co2.R")
