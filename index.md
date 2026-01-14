# Image Bhattarai: GIS & Remote Sensing Portfolio

Welcome to my professional portfolio. Below are my primary research projects.

---

### 🌳 Chicago Park Accessibility Analysis
Integrating municipal and crowdsourced data to evaluate urban green space equity.
This project focuses on creating a unified park feature layer for Chicago by merging official municipal data with OpenStreetMap (OSM).

### Technical GIS Workflow
* **Geodetic Frameworks:** Projected OSM data from `GCS_WGS_1984` to `NAD_1983_2011_StatePlane_Illinois_East`.
* **Data Integration:** Used **Arcade expressions** to fix 12-digit Census ID mismatches.
* **Spatial Join:** Applied the **CLOSEST** operator to resolve spatial nulls between disparate datasets.
* **Quality Control:** Validated data using **Topology Rules** (Must Not Overlap)
### Final Output
![Chicago Park Analysis Results](./output/output_)
* [**View GitHub Repository**](https://github.com/bhattaraicool-spec/bhattaraicool-spec.github.io)

---

### 🛰️ Wetland Permanence Analysis
Automated classification of hydroperiods using multi-seasonal Sentinel-2 imagery.

This project develops an automated method to classify wetland hydroperiods (permanent, vegetated, seasonal) using temporal variability of NDWI derived from multi-season Sentinel-2 imagery.

### Methodology
* **Sensor:** Sentinel-2 Multi-temporal Imagery.
* **Analysis:** Classification based on the temporal variability (Coefficient of Variation) of NDWI.
* **Goal:** Distinguishing between permanent water, seasonal wetlands, and vegetated wetlands.
### Final Output
![Wetland Permanence Analysis Result](./output/output_.jpg)
* [**View GitHub Repository**](https://github.com/bhattaraicool-spec/wetland-permanence_CV_analysis_)
