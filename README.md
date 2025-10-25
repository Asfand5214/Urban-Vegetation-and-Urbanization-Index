# Urban-Vegetation-and-Urbanization-Index

#Overview
This project analyzes **vegetation and urbanization changes over a decade** using satellite imagery and geospatial analytics within **Google Earth Engine (GEE)**.
It focuses on two ket indicators:

- NDVI (Normalized Difference Vegetation Index)
- NDBI (Normalized Difference Built-up Index)

Using Landsat Imagery (from 2013 to 2023), this notebook extracts NDVI and NDBI data for a selected region (Lahore) and visualizes how the city's vegetation and urban density have evolved over time.

# Objectives

1. Compute **NDVI** and **NDBI** for each year using Landsat data.
2. Create **interactive maps** to visualize vegetation and built up areas.
3. Plot **time series trends** of NDVI and NDBI using **Matplotlib**.
4. Analyze the relationship between urban growth and vegetation loss.

# Technical Concepts Covered 

- **Remote Sensing & GIS** using Google Earth Engine (GEE)
-  **Spectral Indices Computation** (NDVI & NDBI)
-  **Temporal Analysis** (10 year trend comparison)
-  **Data Visualization** (Geemap + Matplotlib)
-  **Spatial Statistics** (Mean NDVI/NDBI per year)

# Tools & Libraries

- `earthengine-api`
- `geemap`
- `matplotlib`
- `pandas`
