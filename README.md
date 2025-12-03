# Maui Wildfires

**Fall 2025**\
**Group: Beryl, Wilneris, Maka'ala.**

### Overview

This repository contains code and data processing workflows used to analyze the **2023 Maui Wildfires**, with a focus on:

-   Pre-fire and post-fire **NDVI (Normalized Difference Vegetation Index)** raster analysis

-   Spatial overlays of **Lahaina** and **Upcountry** districts

-   MODIS/VIIRS **fire detection points**

-   Visualization through **static maps** and **animated fire progression GIFs**

-   Geospatial preprocessing steps (cropping, reprojection, masking, animation timelines)

The project uses **RStudio**, leveraging packages such as `sf`, `terra`, `ggplot2`, and `gganimate`

### **Question**

**Which land cover types** (i.e., forest, grasslands, urban) in Maui showed the **greatest resilience** to wildfire damage before and after the 2023 fires? (i.e., does the wildfires upcountry's environment change the outcome?)

### Data Sources

**NDVI** rasters were derived from Sentinel-2. Processed to UTM coordinates and cropped to a Maui-only bounding box.

**Fire detection points** from **NASA FIRMS** (VIIRS or MODIS), filtered by acquisition date:

-   2023-08-08

-   2023-08-09

-   2023-08-10

**District boundaries** of thecounty of Maui district shapefile, transformed to match raster CRS.
