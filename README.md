# Global Water Deficit Index (WDI) Analysis
## Overview

This project presents a global-scale assessment of the Water Deficit Index (WDI) to identify spatial patterns of hydrological stress across the world. The analysis evaluates the imbalance between water demand (evapotranspiration) and water supply (precipitation) to highlight regions experiencing varying degrees of water deficit.

The study was conducted at a global extent, generating continuous spatial outputs that quantify water deficit intensity in millimeters (mm). The results provide insights into arid zones, semi-arid belts, humid regions, and climate-driven water stress hotspots.

## Objectives
- Compute the Water Deficit Index (WDI) globally.
- Identify spatial hotspots of severe water deficit.
- Compare global dryland regions with humid climatic zones.
- Visualize spatial patterns using geospatial raster mapping.

 ## Tools & Technologies Used
1. Python
2. Google Earth Engine (GEE)
3. xarray
4. xee engine
5. NumPy
6. Matplotlib
7. Geospatial raster processing tools

## Dataset Information

The analysis integrates globally available remote sensing and climate datasets:
- Precipitation data (Global climate products)
- Evapotranspiration (ET) datasets
- Global land mask
- Geographic coordinate system: EPSG:4326

### Spatial Characteristics
- Coverage: Global
- Projection: Geographic (WGS 84)
- Units of output: Millimeters (mm)
- Continuous raster output

### Figure 1: Global Water Deficit Index (Thematic Map) 
<img width="516" height="339" alt="image" src="https://github.com/user-attachments/assets/ded24cfd-f9b7-4caf-a853-65edffe40abc" />

- Global distribution of Water Deficit Index (WDI) in millimeters. Warmer colors (orange–red) indicate higher water deficit, while cooler colors (blue–green) represent lower deficit regions.

### Figure 2: Raster Visualization of Global Water Deficit
<img width="820" height="448" alt="image" src="https://github.com/user-attachments/assets/25625de5-e780-4277-8afa-38900e0e8eca" />

- Global raster representation of Water Deficit Index (mm) plotted using longitude and latitude coordinates. Yellow regions indicate severe water deficit, while darker tones represent humid or low-deficit regions.

## Interpretation of Results
1.  High Water Deficit Regions (2000–3200 mm)

Severe deficit zones are observed in:
- Sahara Desert (North Africa)
- Middle East
- Central Asia
- Western United States
- Interior Australia
- Parts of Southern Africa

These regions are characterized by:
- Low precipitation
- High evapotranspiration
- Arid to semi-arid climatic conditions

2. Moderate Water Deficit Regions (1000–2000 mm)

Observed in:
- Indian subcontinent
- Parts of South America
- Mediterranean basin
- Southern United States

These regions experience:
- Seasonal rainfall
- Strong evapotranspiration during dry periods

3. Low Water Deficit / Humid Regions (< 800 mm)

Found in:
- Amazon Basin
- Congo Basin
- Southeast Asia
- Northern Europe
- High-latitude regions

These regions receive:
- High annual precipitation
- Lower net water stress

## Key Insights
1. The global dryland belt (15°–35° latitude) shows consistently high water deficit.
2. Equatorial regions demonstrate lower water deficit due to strong rainfall regimes.
3. Subtropical regions show intense hydrological stress.
4. Australia’s interior stands out as one of the highest deficit zones globally.
5. Northern high latitudes show minimal deficit due to low evapotranspiration.

## Notes & Assumptions
1. Results represent climatological averages, not extreme-event analysis.
2. Water deficit does not directly represent groundwater depletion.
3. Ocean areas were masked.
4. Spatial resolution impacts local-scale interpretation.
5. Differences may occur depending on ET model selection.

## Limitations
- Does not include irrigation or anthropogenic water use.
- Temporal variability not explored (single aggregated representation).
- Climate dataset uncertainties may propagate into WDI.

## Potential Applications
- Drought monitoring
- Climate change impact studies
- Agricultural water planning
- Hydrological modeling
- Water resource management
- Environmental risk assessment

## Future Improvements
- Incorporate time-series trend analysis.
- Include groundwater storage anomalies.
- Compare multi-year climatologies.
- Perform regional-scale validation.
