SOM Field-Scale Mapping Project

This repository contains data and code for field-scale Soil Organic Matter mapping using Sentinel satellite data and machine learning approaches.

### Repository Structure

SOM_Field_Scale/
├── scripts/
│   ├── 01_feature_selection.R
│   ├── 02_RF_model.R
│   ├── 03_XGBoost_model.R
│   └── 04_uncertainty_analysis.R
└── RS_data/
    ├── Sentinel_1/
    │   ├── extracted_data/
    │   └── raster_files/
    └── Sentinel_2/
        ├── extracted_data/
        └── raster_files/


### Contents Description

## Scripts
01_feature_selection.R: RF-Embedded feature selection implementation
02_RF_model.R: Random Forest model training and prediction
03_XGBoost_model.R: XGBoost model implementation
04_uncertainty_analysis.R: Uncertainty assessment using LOOCV iterations

## Remote Sensing Data
Sentinel_1 folder: Multi-temporal radar data (November 2021 - December 2022)
Extracted variables from VV and VH polarizations
Derived indices (R1, R2, RD)

Sentinel_2 folder: Multi-temporal optical data
Spectral bands (Blue, Green, Red, NIR, SWIR)
Vegetation indices (NDVI, SAVI, EVI, etc.)


### Requirements
R version 4.3.1
Required R packages:
ranger
xgboost
caret
terra
raster
tidyverse


### Usage
Clone the repository
Install required R packages
Run scripts in numerical order
Results will be generated in respective output directories

Citation
[Paper under review]
Contact
yassine.bouslihim@gmail.com
