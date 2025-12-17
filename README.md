# Mapping Earth's Volcano Types Near Tectonic Boundaries

## Overview
This project is an interactive ArcGIS Story Map that explores the spatial distribution and types of volcanoes located near tectonic plate boundaries. Volcanoes are among Earth's most dynamic features, and understanding their distribution helps us analyze geological processes, potential hazards, and environmental patterns. This story map provides a visual and analytical exploration of volcano types, their frequency, and spatial patterns in relation to tectonic activity.

![pexels-arthousestudio-4326288](https://github.com/user-attachments/assets/6dfaff7d-db38-48e3-96b2-ff55ff53ed2f)

## Objectives
- Identify which types of volcanoes are most frequent near tectonic plate boundaries.
- Analyze spatial patterns of volcanoes and their correlation with tectonic environments.
- Visualize volcano attributes such as dominant rock type, tectonic setting, and elevation.
- Promote awareness of geological processes shaping Earth's surface.

## Data Sources
- **Global Volcanoes Map** (Point layer) – Smithsonian Volcano Database  
- **Tectonic Plate Boundaries Map** (Line and Polygon layers) – ArcGIS/Smithsonian  
- **Raster Basemap** – High-resolution satellite imagery for visualization context  

## Methodology
1. **Defining Research Question**: Focused on volcano distribution within 300 km of tectonic plate boundaries.  
2. **Data Collection**: Verified reliable datasets from the Smithsonian Volcano Database.  
3. **Data Import**: Imported volcano and tectonic plate layers into ArcGIS.  
4. **Spatial Analysis**: Used overlay and 'Summarize Nearby' tools to calculate volcano counts by type within 300 km of plate boundaries.  
5. **Visualization**: Created interactive maps and bar charts to highlight the frequency of volcano types, rock composition, and tectonic settings.  
6. **Interpretation**: Correlated spatial patterns with geological processes such as subduction zones, mid-ocean ridges, and rift zones.

## Key Findings
- **Stratovolcanoes** are the most frequent type near convergent plate boundaries, commonly forming in subduction zones (e.g., Mount Vesuvius, Pacific Ring of Fire).
<img width="1158" height="505" alt="Screenshot 2025-12-09 at 10 57 50 PM" src="https://github.com/user-attachments/assets/d6d2deed-e60a-43ea-b5a2-6129c06e2ca0" />

- **Submarine volcanoes** are the second most abundant, accounting for ~75% of annual magma reaching Earth's crust.  
- **Calderas** rank third in frequency, formed by explosive eruptions and collapse of underground magma chambers.  
- Volcano distribution patterns closely align with tectonic settings and plate boundaries.

## Ethical Considerations
- Only publicly available geological data were used.  
- No personal or sensitive data were involved.  
- Indigenous Data Sovereignty (IDS) principles are acknowledged, especially in regions overlapping culturally significant volcanic areas.  

## Tools & Technologies
- ArcGIS Online / ArcGIS Pro  
- Spatial Analysis Tools: Overlay Analysis, Summarize Nearby  
- Data Visualization: Interactive maps, bar charts  

