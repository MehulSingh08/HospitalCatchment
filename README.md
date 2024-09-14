This Jupyter notebook aims to evaluate the percentage of the population with access to hospitals and clinics in Timor-Leste, utilizing Python and geospatial analysis. It combines geospatial data from various sources, such as GADM, Facebook population data, and OpenStreetMap, to determine healthcare access within specific administrative regions. The notebook involves spatial visualization, spatial joins, and isochrone analysis to estimate the catchment areas of healthcare facilities. Finally, it calculates the percentage of the population with healthcare access and visualizes the results on an interactive map using Folium.
Importing Required Libraries: The notebook begins by installing and importing the necessary Python libraries, including Folium, pandas, geopandas, and others.

Loading Administrative Boundary Data: It uses the GADM library to obtain geospatial data for Timor-Leste's administrative boundaries, specifically at the first administrative level (e.g., districts or provinces). The data is then visualized on a map.

WorldPop Population Data:

Spatial Join: A spatial join operation is performed to find the population within the selected administrative region (e.g., "Baucau").

Healthcare Facility Data: Healthcare facility data, including hospitals and clinics, is collected from OpenStreetMap using Overpass API. The data is cleaned and prepared for analysis.

Catchment Area Analysis: Isochrone analysis is conducted to estimate the catchment areas of healthcare facilities. This analysis helps determine which population groups have access to healthcare services from each facility.

Population with Access Calculation: The notebook calculates the percentage of the population with access to healthcare services in the selected administrative region.

Interactive Map Visualization: The results are visualized on an interactive map using Folium, displaying healthcare facilities, population with and without access, and administrative boundaries.

The notebook concludes by summarizing the findings and the overall percentage of the population with healthcare access in the selected region.
