# AGRI 3100 – Introduction to Digital Agriculture | Practical Labs | Fall 2026

University of Manitoba — Instructor: Dr. Nasem Badreldin

This repository hosts the practical lab notebooks for **AGRI 3100 – Introduction to Digital Agriculture**. Each notebook is designed to run entirely in **Google Colab**: students do not need a local Python installation. Labs 1–2 use temporary Colab storage; Labs 5–6 use each student's own Google Earth Engine project and Google Drive to save outputs. Click an "Open in Colab" link below to launch a lab directly in your browser.

## Labs

| Lab | Description | Activity | Status / Access |
|:---:|---|---|---|
| Lab 1 | Introduction to Python and Google Colab | Google Colab practical | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab1_Google_Colab.ipynb) |
| Lab 2 | Agricultural Data Handling and Visualization in Digital Agriculture | Google Colab practical | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab2_Agricultural_Data_Handling_Visualization.ipynb) |
| Lab 3 | Data and Instructions | Assignment | **Completed** |
| Lab 4 | Soil Colour | Workshop | **Completed** |
| Lab 5 | Multisensor Satellite Vegetation Indices (Sentinel-2, Landsat, MODIS; NDVI, EVI, SAVI) | Google Colab practical | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab5_Multisensor_Vegetation_Indices.ipynb) |
| Lab 6 | Crop Growth and Phenology (field polygons, multitemporal satellite imagery, vegetation dynamics) | Google Colab practical | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab6_Crop_Growth_Phenology.ipynb) |

**Note:** Labs 3 and 4 were completed as an assignment and workshop, respectively. They do not require Colab notebooks here.

## Getting started

1. For Colab practicals (Labs 1, 2, 5 and 6), click the "Open in Colab" link in the table.
2. Sign in with your Google account when prompted. **For Labs 5–6**, configure your own Earth Engine cloud project, authenticate, and mount your own Google Drive as instructed in the notebook.
3. Run the cells from top to bottom.
4. **Save your work periodically** using **File → Download → Download .ipynb**, so you always have a local backup during the session.
5. When you finish, download the completed `.ipynb` file and follow your instructor's submission instructions in UM Learn.

For Labs 1–2, saving a copy in Google Drive is not required. **Labs 5–6 intentionally save results to your Google Drive**; follow their folder and export instructions.

## Lab 2 dataset

Lab 2 uses a shared soil dataset (`AGRI3100-Soil-Data.xlsx`, ~17 MB) that is **not stored in this repository**. It is hosted in the instructor's Google Drive with view-only access, and the notebook downloads a temporary copy directly into the Colab runtime the first time you run the data-loading cell — no manual upload or Drive mounting required. The notebook reads the `Matched Data` worksheet from that file.

## Repository structure

```
AGRI3100-Practicals-2026/
├── README.md
├── AGRI3100_Lab1_Google_Colab.ipynb
├── AGRI3100_Lab2_Agricultural_Data_Handling_Visualization.ipynb
├── AGRI3100_Lab5_Multisensor_Vegetation_Indices.ipynb
└── AGRI3100_Lab6_Crop_Growth_Phenology.ipynb
```
