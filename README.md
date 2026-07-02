# Nacimiento Wildfire Burned Area Mapping (2023)

Post-fire severity assessment of the February 2023 "Santa Ana" megafire in Nacimiento, Biobío Region, Chile, using Sentinel-2 imagery and the Normalized Burn Ratio (NBR/dNBR) method.

## About

This project maps burn severity across Nacimiento commune following the February 2023 wildfire, one of the most destructive fire events in Chile's recorded history. Pre-fire (January 2023) and post-fire (April 2023) Sentinel-2 imagery were compared using dNBR, classified into standard USGS severity categories.

## Key Results

- Total area analyzed: 90,993.7 ha (full Nacimiento commune)
- Area with detectable burn severity (low to high): ~36,251 ha (39.8% of the commune)
- High severity: 10,708.8 ha (11.8%)
- Moderate-high severity: 7,652.0 ha (8.4%)
- Moderate-low severity: 7,799.6 ha (8.6%)
- Low severity: 10,090.8 ha (11.1%)
- Burn severity is concentrated in a diagonal band from northwest to southeast, consistent with the reported fire spread from Nacimiento toward Santa Juana

## Interactive Map

🔗 [View live map](https://conimoralesg.github.io/nacimiento-wildfire-2023/nacimiento_burn_severity_map.html)

## Data Sources

- Sentinel-2 Surface Reflectance (Copernicus/S2_SR_HARMONIZED)
- GADM administrative boundaries (Nacimiento commune)

## Tools

Google Earth Engine (Python API), geemap, rasterio, Folium, GeoPandas

## Author

Constanza Morales Gajardo
[LinkedIn](https://linkedin.com/in/constanzamoralesgajardo) · [GitHub](https://github.com/conimoralesg)
