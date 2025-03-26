# Mapping Wildfires with AVIRIS Data

This project focuses on identifying and mapping burned areas from wildfires using hyperspectral data from NASA's AVIRIS (Airborne Visible/Infrared Imaging Spectrometer) and thermal anomaly data from VIIRS (Visible Infrared Imaging Radiometer Suite). The analysis is performed using Python tools and open-source geospatial libraries.

## 📁 Project Structure

- `mapping_wildfires.ipynb`: Main analysis notebook for loading, processing, and visualizing wildfire-related remote sensing data.
- `data/`: Folder containing AVIRIS and VIIRS GeoTIFF files and shapefiles (not included in repo for size reasons).
- `figures/`: Folder where output plots and maps are saved.
- `README.md`: Project overview and instructions (this file).

## 🔍 Objectives

- Merge AVIRIS granules to create a continuous mosaic of the affected area.
- Georeference hyperspectral images using associated latitude and longitude bands.
- Overlay VIIRS thermal anomaly data to correlate with AVIRIS observations.
- Visualize the extent of burned areas and assess spectral reflectance differences.

## 📦 Dependencies

Install the required libraries before running the notebook:

```bash
pip install -r requirements.txt
```

## 🛰️ Data Sources
- AVIRIS: https://daac.ornl.gov/AVIRIS/guides/AV3_L1B_RDN.html

## 🗺️ Tools Used
- Python (Jupyter Notebook)
- Rasterio & GDAL (for raster data manipulation)
- GeoPandas (for shapefile processing)
- Matplotlib (for visualization)

## 👤 Author
David — Applied Remote Sensing | NASA Open Science Participant
