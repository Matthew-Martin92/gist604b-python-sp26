# [Project Title]

**Student:** [YOUR NAME]
**Course:** GIST 604B – Open Source GIS
**Module:** [MODULE NUMBER AND NAME]
**University of Arizona**

## Project Description
[2–3 sentences describing what this project is about and what you built or analyzed.]

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


# GIST 604B – Python for GIS

Repository for working with tabular, vector, and raster GIS data using Python.

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   ├── Dockerfile
    ├── data/
    │   ├── neighborhood_samples.geojson
    │   ├── temperature_readings.csv
    │   └── weather_stations.csv
    ├── notebooks/
    │   ├── pandas/
    │   ├── geopandas/
    │   └── rasterio/
    ├── src/
    │   ├── pandas_basics.py
    │   ├── geopandas_basics.py
    │   └── download_real_data.py
    ├── tests/
    │   ├── test_pandas_basics.py
    │   └── test_geopandas_basics.py
    ├── pyproject.toml
    └── uv.lock

## Notes

- Notebooks are for exploration and learning.
- Final implementations are in `src/`.
- Tests validate pandas and GeoPandas functionality.
- Rasterio work is completed entirely in the notebook.
