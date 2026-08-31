# Practical Exam #01 Map Submission

**Date:** October 2024  
**Course:** GIS 3043C  
**Tools:** ArcGIS Pro  

## Overview
Created a professional choropleth map of the lower 48 contiguous United States displaying 1999 population density normalized by area in square miles. The project focused on applying appropriate data classification methods, proper map projections, hierarchy in label styling, and complete layout elements.

## Methods
* **Data Acquisition and Preparation:** Loaded the `Exam_01.aprx` ArcGIS Pro project and imported the `Cities`, `Lakes`, and `States` feature layers from the `USA.gdb` geodatabase. Filtered the view to focus strictly on the lower 48 contiguous states.
* **Spatial Normalization & Classification:** Applied Symbology using Graduated Colors for the `States` theme, normalizing the 1999 population (`POP1999`) by square miles (`AREA`) to accurately represent population density. Utilized a classification method highlighting the top and bottom 20% quintiles.
* **Cartography & Labeling:** Configured an appropriate projection for the contiguous United States, labeled states using two-letter postal abbreviations, and filtered capital cities with custom point symbology and city name labels while hiding non-capital cities.
* **Layout Design & Export:** Integrated all core map elements (neatline, north arrow, scale bar, and a clean legend titled "Persons Per Square Mile"). Exported the final map layout as a flattened PDF at 300 DPI (`Exam_01_Keefe.pdf`).

## Skills Demonstrated
* Choropleth Mapping & Data Normalization
* Advanced Cartographic Design & Visual Hierarchy
* Point and Polygon Feature Label Filtering
* Map Layout & Scale Management

## Outputs
[View Practical Exam Map (PDF)](Exam_01_Keefe.pdf)

---
[← Back to Portfolio](../index.md)
