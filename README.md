# India Air Quality Index Map

## Overview

The choropleth map visually represents the Air Quality Index (AQI) of different states in India, incorporating various features such as agricultural lands, industrial areas, railways, aqueducts, landfills, and areas under construction. This project aims to assist environmentalists and policymakers in assessing pollution rates, facilitating informed decisions, and implementing measures in regions most affected by pollution.

## Problem Statement

Develop a map that visually represents pollution rates based on AQI, aiding environmentalists and policymakers in identifying and addressing regions with high pollution levels.

## Data Sources

- [Tomorrow.io Weather - Air quality and pollen in Leh, Ladakh](https://www.tomorrow.io/weather/IN/LA/Leh/132762/health/)
- [Air Matters - Andaman and Nicobar Islands real-time AQI](https://air-quality.com/place/india//af354392?lang=en&standard=aqi_us)
- [AnujTiwari - India State and Country Shapefile](https://github.com/AnujTiwari/India-State-and-Country-Shapefile-Updated-Jan-2020)
- [AQI.in - India Air Quality Index](https://www.aqi.in/ca/dashboard/india)
- [GeoWeb - Aqueducts and Canals, India, 2016](https://geodata.mit.edu/catalog/stanford-hm158hv9062)
- [GeoWeb - Railroads, India, 2016](https://geodata.mit.edu/catalog/stanford-zf546fb9425)
- [Air Matters - Lakshadweep real-time AQI](https://air-quality.com/place/india//0b51a93d?lang=en&standard=aqi_us)
- [IQAir - Leh Air Quality Index](https://www.iqair.com/ca/india/jammu-and-kashmir/leh)
- [IGIS Map - Agricultural Lands](https://map.igismap.com/gis-data/133334/india/agricultural_lands_point)
- [IGIS Map - Industrial Landuse](https://map.igismap.com/gis-data/133334/india/industrial_landuse_point)
- [IGIS Map - Railways](https://map.igismap.com/gis-data/133334/india/railways_polyline)
- [IGIS Map - Aqueducts and Canals](https://map.igismap.com/gis-data/133334/india/aqueducts_canals_polyline)
- [IGIS Map - Landfills](https://map.igismap.com/gis-data/133334/india/landfills_polygon)
- [IGIS Map - Areas Under Construction](https://map.igismap.com/gis-data/133334/india/areas_under_construction_polygon)

## Metadata for Each Layer

- **Agricultural Land (POINT):** Represents agricultural sites across India.
- **Industrial Landuse (POINT):** Represents industrial landuse sites across India.
- **Railways (POLYLINE):** Network of rail lines across India.
- **Aqueducts and Canals (POLYLINE):** Network of aqueducts and canals across India.
- **Landfills (POLYGON):** Represents landfill areas across India.
- **Areas Under Construction (POLYGON):** Represents areas under construction across India.

## Project Design

The map combines different feature layers to visually represent pollution rates in India. The features include points, polylines, and polygons representing agricultural lands, industrial areas, railways, aqueducts, landfills, and areas under construction. The AQI data was joined with the shapefile of Indian states to display pollution rates. Graduated colors were used for visual representation, with a color scheme indicating lower to higher AQI values. Various symbols and colors were used to represent different features, enhancing map interpretability.

## Web Map Elements

- **Compass:** Not included as online platforms provide tools that serve the same purpose.
- **Scale:** Not included due to the availability of online tools for distance measurement.
- **Title:** Not separately mentioned as it is displayed on the online platform.
- **Neat Line:** Not included for an interactive web map.
- **Legend:** Included to help users understand the represented data and color-coding.

## Usage

Visit the web map to explore the Air Quality Index and pollution rates in different states of India.

[Explore India Air Quality Map](https://utoronto.maps.arcgis.com/apps/instant/sidebar/index.html?appid=291612e3826c4bb49819a1759f67c36d)

## License

This project is licensed under the [MIT License](LICENSE).

