# Python for GIS  

**Student:** Matthew Martin  
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 3: Python GIS & Containerization  
**University of Arizona**  

## Project Description
[2–3 sentences describing what this project is about and what you built or analyzed.]
Repository for working with tabular, vector, and raster GIS data using Python.  

## Tools and Technologies
- [Tool 1, e.g. QGIS, PostGIS, GeoPandas, Leaflet]
- [Tool 2]
- [Tool 3]

## What I Did
[3–5 bullet points summarizing the key tasks completed in this assignment.]

## How to View / Run
[Instructions for viewing the project. For example:
- Link to live GitHub Pages site (if applicable)
- How to run a Python script
- How to open the map]

## Repository Structure
[Brief description of folders and key files]

## Repository Structure

    .
    ├── .devcontainer
    │   ├── devcontainer.json
    │   └── Dockerfile
    ├── data/
    │   ├── cities/
    │       └── ne_cities_us.geojson
    │   ├── ecoregions/
    │       └── epa_level3_western_us.geojson
    │   ├── protected_areas/
    │       └── national_parks_major.geojson
    │   ├── temp/
    │       ├── neighborhood_samples.geojson
    │       ├── temperature_readings.csv
    │       └── weather_stations.csv
    ├── notebooks/
    │   ├── pandas/
    │       ├── 01_function_load_and_explore_gis_data.ipynb
    │       ├── 02_function_filter_environmental_data.ipynb
    │       ├── 03_function_calculate_station_statistics.ipynb
    │       ├── 04_function_join_station_data.ipynb
    │   ├── geopandas/
    │       ├── 00_download_real_data.ipynb
    │       ├── 01_function_load_spatial_data.ipynb
    │       ├── 02_function_explore_properties.ipynb
    │       ├── 03_function_transform_crs.ipynb
    │       ├── 04_function_geometry_operations.ipynb
    │       ├── 05_function_spatial_relationships.ipynb
    │       ├── 06_function_spatial_joins.ipynb
    │       ├── 07_function_overlay_and_visualize.ipynb
    │       └── overlay_test.png
    │   ├── rasterio/
    │       └── remote_sensing_workflow.ip
    ├── src/
    │   ├── pandas_basics.py
    │   ├── geopandas_basics.py
    │   └── download_real_data.py
    ├── tests/
    │   ├── test_pandas_basics.py
    │   └── test_geopandas_basics.py
    ├── README.md
    ├── pyproject.toml
    └── uv.lock

## Notes

- Notebooks are for exploration and learning.
- Final implementations are in `src/`.
- Tests validate pandas and GeoPandas functionality.
- Rasterio work is completed entirely in the notebook.
