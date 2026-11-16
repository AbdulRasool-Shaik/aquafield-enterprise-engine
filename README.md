# AquaField Enterprise Intelligence Engine
End-to-end spatial telemetry and deep learning intelligence platform designed for agritech and hydrological decision-support systems (`aquaWISE` & `fieldWISE`).

## Architecture & Tech Stack
- **Geospatial Ingestion:** `Rasterio` for multi-band satellite GeoTIFF processing and NDWI water index calculation in UTM Zone 44N (`EPSG:32644`).
- **Spatial Vector Joins:** `GeoPandas` for linking IoT telemetry station points to administrative district polygons.
- **Deep Learning Core:** `TensorFlow / Keras` 4-band convolutional U-Net for surface water segmentation and spatial feature extraction.
- **Production Serving:** `FastAPI` REST microservice with Pydantic validation schemas for real-time flood risk scoring.

## Author
**Shaik Abdul Rasool**  
B.Tech Computer Science and Engineering, RGUKT Basar
