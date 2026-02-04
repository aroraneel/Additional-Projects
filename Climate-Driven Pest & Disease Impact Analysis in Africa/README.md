# Climate-Driven Pest & Disease Impact Analysis in Africa

## Overview
This project analyzes **climate-driven pest and disease impacts on agriculture across Africa** using geospatial datasets and scenario-based projections.  
It combines **geographic boundary data**, **pest-yield impact projections**, and **climate model outputs** to identify vulnerable crops, countries, and emerging risk hotspots.

---

## Objectives
- Identify **most vulnerable crops and countries** to pest pressure
- Analyze **temporal changes** (2040 → 2060)
- Compare impacts under **different climate scenarios (SSP245 vs SSP585)**
- Detect **emerging pest-risk hotspots**
- Support **food security and adaptation planning**

---

## Data Sources
- GAUL Africa geographic boundary datasets (TopoJSON)
- Pest & disease yield impact data (AAA Digital Atlas)
- Pest performance projections by climate models
- Scenario-based projections (SSP245, SSP585 where available)

---

## Methodology
1. **Geospatial Data Processing**
   - Load and merge GAUL boundary datasets
   - Clean geometry and attribute fields

2. **Data Preprocessing**
   - Handle missing values
   - Normalize numerical features
   - Encode categorical variables

3. **Analytical Framework**
   - Crop-level vulnerability analysis
   - Country–crop risk assessment
   - Time-based comparison (2040 vs 2060)
   - Scenario comparison (moderate vs high emissions)
   - Model agreement analysis

4. **Visualization**
   - Bar charts & boxplots
   - Heatmaps (Country × Crop)
   - Time-series trends
   - Scenario comparison plots

---

## Key Insights
- Pest pressure **increases across all African regions** by 2060
- Certain crops show **consistently higher vulnerability**
- High-emission scenarios (SSP585) result in **significantly larger impacts**
- Some countries emerge as **new high-risk hotspots**
- Climate models show **strong agreement on upward pest trends**

---

## Tools & Libraries
- Python
- Pandas, NumPy
- GeoPandas
- Matplotlib, Seaborn
- Scikit-learn

---

## Applications
- Climate adaptation planning
- Agricultural risk assessment
- Policy decision support
- Integrated Pest Management (IPM) prioritization
- Food security analysis

---

## Author
**Neel Arora**  
BCA Undergraduate | Data Science & Machine Learning Enthusiast  

---

## Notes
- This project is **analytical and exploratory**, designed as a **research-oriented proof of concept**
- Results depend on climate model assumptions and scenario availability
- Intended for **insight generation**, not operational forecasting
