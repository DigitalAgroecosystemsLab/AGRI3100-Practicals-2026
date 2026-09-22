# AGRI 3100 – Introduction to Digital Agriculture | Practical Labs | Fall 2026

University of Manitoba — Instructor: Dr. Nasem Badreldin

This repository hosts the practical lab notebooks for **AGRI 3100 – Introduction to Digital Agriculture**. Each notebook is designed to run entirely in **Google Colab**: students do not need a local Python installation, and no files need to be uploaded or saved to a personal Google Drive. Click an "Open in Colab" link below to launch a lab directly in your browser.

## Labs

| Lab | Description | Open in Colab |
|---|---|---|
| Lab 1 | Introduction to Python and Google Colab | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab1_Google_Colab.ipynb) |
| Lab 2 | Agricultural Data Handling and Visualization in Digital Agriculture | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab2_Agricultural_Data_Handling_Visualization.ipynb) |

Direct links:

- Lab 1 – Introduction to Python and Google Colab: https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab1_Google_Colab.ipynb
- Lab 2 – Agricultural Data Handling and Visualization in Digital Agriculture: https://colab.research.google.com/github/DigitalAgroecosystemsLab/AGRI3100-Practicals-2026/blob/main/AGRI3100_Lab2_Agricultural_Data_Handling_Visualization.ipynb

## Getting started

1. Click the "Open in Colab" link for the lab you are working on.
2. Sign in with your Google account when prompted (this is only required to *run* the notebook — you are not saving anything to your Drive).
3. Run the cells from top to bottom.
4. **Save your work periodically** using **File → Download → Download .ipynb**, so you always have a local backup during the session.
5. When you finish, download the completed `.ipynb` file and submit it through UM Learn.

You do **not** need to use "Save a copy in Drive" — each notebook runs in a temporary Colab session and tells you when and how to save a backup.

## Lab 2 dataset

Lab 2 uses a shared soil dataset (`AGRI3100-Soil-Data.xlsx`, ~17 MB) that is **not stored in this repository**. It is hosted in the instructor's Google Drive with view-only access, and the notebook downloads a temporary copy directly into the Colab runtime the first time you run the data-loading cell — no manual upload or Drive mounting required. The notebook reads the `Matched Data` worksheet from that file.

## Repository structure

```
AGRI3100-Practicals-2026/
├── README.md
├── AGRI3100_Lab1_Google_Colab.ipynb
└── AGRI3100_Lab2_Agricultural_Data_Handling_Visualization.ipynb
```
