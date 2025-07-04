🗺️ Satellite Image Overlay with Roads & Points

This project visualizes geospatial data by overlaying road and point shapefiles on a satellite image (GeoTIFF) using Rasterio, GeoPandas, and Matplotlib.

🔍 Overview

Loads a satellite image (.tif) using Rasterio

Loads vector layers (roads and points) using GeoPandas

Overlays shapefiles on the satellite image with clear color-coding and legend

Produces a clean, styled map with roads in red and points in pink

📦 Dependencies

rasterio

geopandas

matplotlib

🚀 Usage

Initialize the MapOverlay class with your file paths.

Call .load_data() to load raster and vector layers.

Call .overlay() to display the final map.

📸 Output

A static map with:

Satellite image as the base

Red lines for roads

Pink dots for point features 
