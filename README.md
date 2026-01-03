# asiatic-elephant-habitat-india
GIS-based analysis of Asiatic elephant distribution and forest habitat in India
# Spatial Analysis of Asiatic Elephant Habitat in India 

## Overview
This project presents a GIS-based spatial analysis of Asiatic elephant (*Elephas maximus*) distribution in India, examining its relationship with forest habitat and protected areas. The study uses open-access spatial data and QGIS to explore habitat dependence and conservation relevance at a national scale.

The project was developed as a learning and portfolio exercise in conservation GIS and spatial ecology.

---

## Objectives
- Map the spatial distribution of Asiatic elephant occurrence records across India  
- Identify forest habitat using land use / land cover (LULC) data  
- Assess forest availability within and around protected areas (5 km buffer)  
- Highlight areas that may function as potential habitat linkages or corridors  

---

## Study Area
The analysis covers the entire geographic extent of India, with particular relevance to regions such as the Western Ghats, Central India, Eastern Ghats, and North-East India where elephant populations are known to occur.

---

## Data Sources
- **Elephant occurrence data:** Global Biodiversity Information Facility (GBIF)  
- **Land Use / Land Cover:** ESA / Bhuvan LULC datasets  
- **Protected Areas:** World Database on Protected Areas (WDPA)  
- **Administrative boundary:** India national boundary (ADM0)

All datasets used are open-access and intended for academic and research purposes.

---

## Methodology
- Elephant occurrence records were cleaned and mapped as point features  
- LULC raster data were examined and forest-related classes extracted  
- A binary forest habitat layer (forest / non-forest) was generated  
- Protected areas were merged and buffered by 5 km to represent zones of ecological influence  
- Forest cover within protected area buffers was analyzed  
- Thematic maps were produced to visualize spatial relationships  

All analyses were carried out using **QGIS 3.40 LTR**.

---

## Outputs
- Elephant occurrence distribution map  
- Forest habitat distribution map  
- Forest cover within protected area buffer zones (5 km)  


---

## Key Insights
- Elephant occurrences show strong spatial association with forested landscapes  
- Significant forest cover exists outside protected areas, indicating the importance of buffer zones  
- Findings emphasize the need for landscape-level conservation beyond protected boundaries  

---

## Tools Used
- QGIS 3.40 LTR  
- Raster and vector spatial analysis  
- Zonal statistics and buffering  

---

## Author
Akanksha Verma
(MSc Zoology | Conservation & GIS enthusiast)

---

## Disclaimer
This project is for academic and learning purposes. Occurrence data may be spatially biased.
