# Groundwater-Potential-Zonation-using-GIS-Based-Multi-Criteria-Analysis-P4-_ISA-Internship

# 🌍 Groundwater Potential Mapping using Google Earth Engine, Remote Sensing & GIS

A geospatial analysis project that identifies groundwater potential zones using **Google Earth Engine (GEE)**, **Remote Sensing**, **Geographic Information Systems (GIS)**, and **Weighted Overlay Analysis**. The project integrates multiple environmental factors to generate a groundwater potential map for **Khordha District, Odisha, India**. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

Groundwater is one of the most important freshwater resources for domestic, agricultural, and industrial use. This project uses satellite imagery and geospatial analysis to estimate groundwater availability by combining multiple thematic layers.

The workflow integrates:

- 🛰️ Digital Elevation Model (DEM)
- ⛰️ Slope Analysis
- 🌱 Normalized Difference Vegetation Index (NDVI)
- 🏞️ Land Use / Land Cover (LULC)

These layers are combined using a **Weighted Overlay Analysis** to generate the **Groundwater Potential Index (GWPI)** and classify the study area into groundwater potential zones. :contentReference[oaicite:1]{index=1}

---

## 🎯 Objectives

- Delineate the Area of Interest (AOI)
- Generate DEM, Slope, NDVI, and LULC layers
- Analyze terrain and vegetation characteristics
- Perform Weighted Overlay Analysis
- Generate Groundwater Potential Index (GWPI)
- Classify groundwater potential into five categories
- Demonstrate the use of Google Earth Engine for groundwater assessment :contentReference[oaicite:2]{index=2}

---

## 📍 Study Area

**Khordha District, Odisha, India**

The study area was defined as a polygon in Google Earth Engine and all datasets were clipped to this Area of Interest (AOI). :contentReference[oaicite:3]{index=3}

---

## 🛠️ Technologies Used

- Google Earth Engine (GEE)
- Remote Sensing
- Geographic Information Systems (GIS)
- JavaScript (GEE Code Editor)

---

## 📊 Datasets

| Dataset | Source | Purpose |
|----------|--------|---------|
| SRTM DEM | NASA | Elevation & Slope |
| Sentinel-2 | ESA | NDVI Calculation |
| ESA WorldCover 2021 | ESA | Land Use/Land Cover | :contentReference[oaicite:4]{index=4}

---

## 🔄 Methodology

1. Select Study Area (AOI)
2. Collect Satellite Data
3. Generate DEM
4. Calculate Slope
5. Compute NDVI
6. Generate LULC Map
7. Perform Weighted Overlay Analysis
8. Calculate Groundwater Potential Index (GWPI)
9. Classify Groundwater Potential Zones :contentReference[oaicite:5]{index=5}

---

## ⚖️ Weighted Overlay

The following weights were assigned during groundwater potential analysis:

| Parameter | Weight |
|----------|-------:|
| NDVI | 30% |
| Slope | 25% |
| DEM | 20% |
| LULC | 25% | :contentReference[oaicite:6]{index=6}

---

## 📈 Groundwater Potential Classes

The final Groundwater Potential Index (GWPI) was classified into:

- Very Low
- Low
- Moderate
- High
- Very High :contentReference[oaicite:7]{index=7}

---

## 📂 Repository Structure

```
Groundwater-Potential-Mapping/
│
├── data/               # Input datasets (optional)
├── scripts/            # Google Earth Engine scripts
├── results/            # Generated maps and outputs
├── images/             # Figures and screenshots
├── report/             # Internship report
├── README.md
└── LICENSE
```

---

## 📸 Results

The project generates:

- Digital Elevation Model (DEM)
- Slope Map
- NDVI Map
- Land Use/Land Cover Map
- Groundwater Potential Index (GWPI)
- Groundwater Potential Zones Map :contentReference[oaicite:8]{index=8}

---

## 🚀 Future Improvements

Future versions of the project can include additional parameters such as:

- Rainfall
- Soil Type
- Geology
- Drainage Density
- Lineament Density

These additions can improve the accuracy of groundwater potential mapping. :contentReference[oaicite:9]{index=9}

---

## 📄 Report

The complete internship report is available in this repository. :contentReference[oaicite:10]{index=10}

---

## 👨‍💻 Author

**Simran Osta**

Department of Computer Science and Engineering  
XIM University, Bhubaneswar

---

## ⭐ If you found this project useful

Give this repository a ⭐ and feel free to fork it for your own geospatial analysis projects.
