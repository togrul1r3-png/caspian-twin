# 🌊 Caspian-Twin 3D: AI-Powered Digital Twin of the Baku Coastline

**Caspian-Twin** is an end-to-end geospatial research project combining **Google Earth Engine**, **PyTorch U-Net** semantic segmentation, and **MapLibre GL JS** 3D visualization to quantify and forecast Caspian Sea shoreline retreat along Baku and the Absheron Peninsula (2019–2035).

### 🔗 Live Interactive 3D Portal
👉 **[Launch Caspian-Twin 3D Map](https://togrul1r3-png.github.io/caspian-twin/)**

### 🔬 Key Scientific Findings
- **Segmentation Accuracy:** `Val IoU = 0.760` (`U-Net` with `ResNet34` encoder trained on 450 multispectral Sentinel-2 patches).
- **Retreat Velocity (LRR):** **8.53 m/year** across **1,797 virtual coastal stations** (`R² = 0.948`, `p = 0.0051`).
- **2035 Forecast:** Projected cumulative shoreline retreat of **+131.8 meters** relative to the 2019 baseline.
- **Infrastructure Risk Assessment:** Automated proximity and siltation risk modeling for 7 critical coastal assets (Port of Hovsan, Zigh Lagoon, Gum Island, Baku Boulevard, National Flag Square, Bibiheybat, and Shikhov).

### 🛠️ Tech Stack
- **Remote Sensing:** Google Earth Engine (`COPERNICUS/S2_SR_HARMONIZED`, 10 m resolution, bands B2, B3, B4, B8, B11, UTM Zone 39N `EPSG:32639`).
- **Deep Learning & GIS:** Python, PyTorch, `segmentation-models-pytorch`, `Rasterio`, `GeoPandas`, `Shapely`, `SciPy` (`roadtousaig.ipynb`).
- **3D Web-GIS:** HTML5, CSS3, JavaScript, MapLibre GL JS (`index.html`).
