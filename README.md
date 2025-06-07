# -SPATIOTEMPORAL-ANALYSIS-OF-NDVI-CHAGES-WITH-RAINFALL
This project focuses on understanding how vegetation in Vadagam, Banaskantha (Gujarat) responds to rainfall over time using NDVI (Normalized Difference Vegetation Index). The study covers the period from 2021 to 2024 and uses remote sensing and GIS tools to analyze these changes.

The idea came from observing how agriculture in the region heavily depends on seasonal rainfall. Since NDVI is a good indicator of plant health, analyzing it alongside rainfall helps identify patterns in vegetation growth or stress.

Key tools used:

QGIS for NDVI calculation and reclassification

Copernicus Browser for downloading satellite images

IMDLIB for rainfall data

Python (with libraries like Rasterio, NumPy, and Matplotlib) for analysis and visualization

Main steps in the project:

Download satellite images (Sentinel-2) and rainfall data (IMD)

Calculate NDVI using Red and NIR bands

Reclassify NDVI values to categorize vegetation levels

Compare yearly NDVI changes with rainfall using Python scripts

Visualize trends using maps, graphs, and charts
