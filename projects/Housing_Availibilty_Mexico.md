# Lab 2, Housing Availability in Mexico

**Date:** September 2024
**Course:** GIS 3043C
**Tools:** ArcGIS Pro

## Overview
Prepare a map of Mexico showing housing density (expressed as persons per household) for 1990.

## Methods
* **Data Acquisition and Preparation:** Acquired 1990 census spatial and tabular data for Mexico, including state boundaries, population fields (`POP1990`), and housing unit counts (`HSE_UNIT90`).
* **Spatial Normalization & Classification:** Utilized ArcGIS Pro to calculate housing density (persons per household) by dividing population by housing units. Applied a 5-class quintile (Quantile) classification scheme for the choropleth map.
* **Feature Filtering & Cartography:** Filtered state capital cities using a definition query, established a clear visual hierarchy between state and city labels, and integrated hydrography layers (rivers and lakes) without labeling. 
* **Layout & Export:** Configured an appropriate map projection for Mexico, added a customized legend, scale bar, north arrow, and neatline, and exported the final layout to a high-resolution PDF (`Lab_02_Keefe.pdf`).

## Skills Demonstrated
* Choropleth Mapping & Data Normalization
* Attribute Filtering & Definition Queries
* Cartographic Design & Visual Hierarchy

## Outputs
![View Lab 2 Map & Report](..?images/Lab_02_Keefe.pdf)

---
[← Back to Portfolio](../index.md)
