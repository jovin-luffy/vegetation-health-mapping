# vegetation-health-mapping
Analyzing vegetation health, land cover, and drought conditions using spectral band math and multi-temporal satellite imagery.
# NDVI Calculation & Vegetation Analysis using Google Earth Engine 🌍🌿

## 📌 Project Overview
This project calculates and maps the **Normalized Difference Vegetation Index (NDVI)** to assess vegetation health, density, and land cover variations. By processing multi-spectral satellite imagery in Google Earth Engine (GEE), this tool provides a quantitative analysis of live green vegetation, which is essential for agricultural monitoring, drought estimation, and environmental assessments.

## 🛠️ Tech Stack & Tools
* **Platform:** Google Earth Engine (GEE)
* **Programming Language:** JavaScript (GEE API)
* **Data Sources:** Multi-spectral satellite imagery (e.g., Sentinel-2 / Landsat)
* **Core Techniques:** Spectral Band Math, Remote Sensing Algorithms, Cloud Masking, Spatial Data Visualization

## 🔬 Data Pipeline & Methodology
1. **Data Acquisition:** Filtered high-resolution satellite imagery collections for the target region and time period.
2. **Preprocessing:** Applied cloud and shadow masking to ensure accurate pixel values and clean analysis-ready data.
3. **Algorithmic Computation:** Programmatically calculated the NDVI using the standard band math equation: 
   `NDVI = (NIR - Red) / (NIR + Red)`
4. **Classification & Rendering:** Applied a custom color palette to visually classify pixel values, effectively differentiating between water bodies, barren land, sparse vegetation, and dense forest canopies.
5. **Spatial Analysis:** Exported and visualized the resulting layers to monitor vegetation dynamics across the selected Region of Interest (ROI).

## 🚀 How to Execute the Code
1. Open the [Google Earth Engine Code Editor](https://code.earthengine.google.com/).
2. Copy the contents of the `script.js` file from this repository.
3. Paste the script into your GEE Code Editor.
4. Click **Run** to execute the spectral processing pipeline and render the NDVI map layers.

## 📊 Results & Visualization
*(Upload a screenshot of your final Earth Engine map showing the colored NDVI layers—e.g., green for dense vegetation, brown/white for barren land—and link it here: `![NDVI Map](map_image.png)`)*

---
**Author:** Jovin Jeffley 
**Contact:** jovinjeffley06@gmail.com | [LinkedIn](https://www.linkedin.com/in/jovin-jeffley)
