# SDA_SuitabilityAnalysis_HazardousWaste

##Workflow
1. Add all layers and check if right extent and projection
2. Reproject all Layers to 3301
  - Reprojected Protected Areas from 3035 to 3301
  - Reprojected Soil texture Type Dataset (FAO) from 4326 to 3301

3. Clip all vector data to borders of estonia
  - Clipped protectedAreas to Estonian land border
  - DISCARDED DATASET: Clipped standing surface water to estonian land borders
  - Clipped Rivers to Borders
  - Clipped LandUse to Borders
  - SoilType_Estonia3301 - Necessary? Check again
5. 

filter out surface water
3. Convert all Vector Dataset to Raster datasets





Water & Wetlands --> Surface Water - Unsuitable

























1. Define Exclusion Criteria

![image](https://github.com/pknirsch/SDA_SuitabilityAnalysis_HazardousWaste/assets/41683047/7ab8fbe3-f681-4e62-b18d-592b836eb53a)


ProtectedAreas_Estonia.gpkg




Evaluation Criteria?:
- Elevation - high better- distance from sea level can cause pollution problems


https://journals.sagepub.com/doi/10.1177/0734242X221124069

https://geoportaal.maaamet.ee/eng/spatial-data/geological-data/geological-base-map-1-50-000/thematic-maps-of-the-geological-base-map-p726.html

https://geoportaal.maaamet.ee/eng/Spatial-Data/Geological-Data/Geological-maps-1-400-000/Download-Geological-Maps-Data-p543.html

https://xgis.maaamet.ee/xgis2/page/app/geoloogia400k
