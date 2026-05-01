# Python for GIS  

**Student:** Matthew Martin  
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 3: Python GIS & Containerization  
**University of Arizona**  

## Project Description
This project contains workable notebooks using Pandas, Geopandas, and Rasterio. It runs through tutorials in the notebooks to learn how to incorporate Python code in the repository. This code allows us to work with tabular, vector, and raster GIS data within the notebooks.

## Tools and Technologies
- Python
- Jupyter Notebooks
- Geopandas
- Pandas
- Rasterio

## What I Did

- Completed notebooks in the pandas folder to load, explore, create functions to fileter and calculate environmental station data.
- Completed notebooks in the Geopandas folder to do the following:
    - download, load, and explore spatial data
    - perform a transform and geometry options on the data
    - perform spatial relationships and joins on data tables
    - create visualizations on the data.
      
## How to View / Run
[Instructions for viewing the project. For example:
- Link to live GitHub Pages site (if applicable)
- How to run a Python script
- How to open the map]

## Repository Structure
THe data folder contains the data used in the python code from the notebooks folders. The Pandas folder inlcudes Jupyter notebooks to teach and walk through the use of python and pandas GIS workflows. The Geopandas does similar workflows, using the Geopandas environment. Each of these folders contain notebooks to work through several tutorials. The src folder contains the code fort he funtions implemented in the workbooks. The test folder contains the code to test througout the notebooks.

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

