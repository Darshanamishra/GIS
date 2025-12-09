# 📍 California Wildfire Impact Analysis (2012–2022)

This project visualizes how much land within each California county burned in wildfires over a ten-year period. Wildfire perimeters were processed in ArcGIS Pro to calculate **total acres burned per county**, summarized into **% of county land affected**, and mapped using Natural Breaks classification.

The output clearly highlights regional patterns — northern and interior counties show much higher burn percentages compared to many coastal areas.

---

## 🔥 What This Project Demonstrates

- GIS-based wildfire impact assessment  
- Spatial overlay + area calculations  
- Attribute summarization and % metrics  
- Cartographic map design and labeling  
- End-to-end ArcGIS Pro workflow  

---

## 🛠 Tools & Methods

| Technique | Purpose |
|----------|----------|
| **ArcGIS Pro** | Main analysis & map visualization |
| Dissolve | Combine wildfire perimeters |
| Intersect | Extract burned areas per county |
| Calculate Geometry | Burned area in acres |
| Summary Statistics | Total acres burned per county |
| Field Calculator | Percent burned calculation |
| Map Layout | Symbology, labels, legend, scale bar |

---

## 📊 Workflow Summary

1. Loaded wildfire & county boundary datasets  
2. Dissolved wildfire perimeters into one burnt area polygon  
3. Intersected with county boundaries  
4. Calculated acreage and summarized totals by county  
5. Joined summary table back to counties + % burned field created  
6. Classified data into **five classes using Natural Breaks (Jenks)**  
7. Map layout designed with labels, legend, and metadata  
8. Exported map as PDF and packaged ArcGIS project  

---

### **Percentage of California County Land Burned (2012–2022)**

🖼 Map Preview:

<img src="https://raw.githubusercontent.com/Darshanamishra/GIS/main/California_FierImapct_Map.png" width="600">

