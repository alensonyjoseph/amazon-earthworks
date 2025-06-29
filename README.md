# 🏆 Hidden Amazon Earthworks

## OpenAI → Z Challenge

We fuse **SRTM DEM terrain micro-relief**, **Sentinel-2 spectral anomalies**, and **NASA GEDI canopy breaks** — ranked by GPT-4.1 — to reveal **five previously undocumented archaeological sites across Brazil and Bolivia**.

---

## 🚀 Project Highlights

* 📍 **Five new candidate earthwork sites** detected in Brazil & Bolivia, each cross-validated with DEM, NDVI, and GEDI canopy signatures.
* 🛰️ **Based on open global satellite & LiDAR data.**
* 🤖 **GPT-4.1 ensemble used to prioritize multi-layer anomalies.**
* 💡 **Fully reproducible on free platforms (Kaggle, local Python).**

---

## 📂 Repository Contents

| File                     | Purpose                                           |
|---------------------------|--------------------------------------------------|
| `amazon_geo_anomaly.ipynb` | Main notebook: downloads tiles, processes data, outputs CSV + GeoJSON + figures |
| `top5_sites.csv`           | Table with site name, lat/lon, key evidence      |
| `top5_sites.geojson`       | Easy import to Google Earth or QGIS              |
| `hillshade_demo.png`       | Example DEM pseudo-hillshade                     |
| `ndvi_demo.png`            | Example NDVI vegetation anomaly                  |
| `gedi_demo.png`            | Example GEDI canopy scatter                      |
| `LICENSE.txt`              | CC0 1.0 Universal (public domain dedication)     |
| `DOI_tile_list.txt`        | References for SRTM, Sentinel-2, GEDI, plus key papers |

---

## ⚙️ How to Reproduce

1. **Clone or download**
    ```bash
    git clone https://github.com/YOUR_USERNAME/amazon-earthworks.git
    cd amazon-earthworks
    ```

2. **Install Python deps**
    ```bash
    pip install numpy pandas geopandas rasterio matplotlib
    ```

3. **Run the notebook**
    - Launch Jupyter Lab or VS Code.
    - Open `amazon_geo_anomaly.ipynb` and run all cells.

    **Outputs:**
    * CSV & GeoJSON of sites
    * PNG plots for DEM, NDVI, GEDI

---

## 🌍 Data Sources

* **SRTM DEM:** NASA/USGS open 30 m elevation grids (via EarthExplorer)
* **Sentinel-2 MSI L2A:** ESA Copernicus imagery from AWS Registry
* **NASA GEDI LiDAR RH90:** ORNL DAAC (via GEDI Data Pool)
* **Known site mask & ML surface:** Walker et al. (*PeerJ 2023*), Peripato et al. (*Science 2023*)

(Full tile IDs + DOIs in `DOI_tile_list.txt`.)

---

## 📝 License

All code, text, and figures are under:


✅ No restrictions — reuse, adapt, or publish anywhere.

---

## ✉️ Contact

Created for the **OpenAI → Z Challenge**  
by **Alen Sony Joseph / Team Seeker**

📧 mr.alen.sony.joseph@gmail.com
