# Bharatiya Antariksh Hackathon 2024

## Overview
A comprehensive tool for spectral classification of Chandrayaan-2 IIRS (Imaging Infrared Spectrometer) data using AI/ML techniques to understand the geological diversity of the Moon. Developed by Team Coding Brigades from LDRP Institute of Technology and Research, Gandhinagar.

## Problem Statement
Current solutions lack intuitive interfaces for analyzing lunar spectral data, comparing regions, performing time-series analysis, and detecting anomalies, which limits comprehensive understanding of lunar mineralogy.

## Features
- **Spectral Classification Overlays** on lunar selenographic maps
- **Time-series Spectral Analysis** for tracking dynamic lunar processes
- **Lunar Region-wise Analysis** for comparing different areas
- **Automated Spectral Classification Validation** using AI
- **Research and Findings Reporting** system
- **Spectral Anomaly Detection** to identify unique mineralogical features

## Technical Architecture
- Data processing pipeline for IIRS data (256 spectral bands)
- Radiance to reflectance conversion
- AI/ML models for classification and anomaly detection
- Interactive visualization interface

## Data Understanding
The system processes IIRS data organized in 3,172 folders containing:
- **Data**: .qub files (radiance images) and .hdr files for 256 bands
- **Browse**: Thumbnail images for quick reference
- **Geometry**: Spatial context (longitude, latitude, pixel size)
- **Miscellaneous**: Metadata for radiance to reflectance conversion

## Technologies Used
- **Backend**: Python, GDAL, PyTorch, SciPy, Matlab
- **Data Analysis**: Seaborn, Matplotlib, GeoPandas
- **Frontend**: NextJS, NodeJS

## Use Cases
- Monitoring lunar surface temporal variations
- Targeted exploration of lunar regions
- Facilitating collaborative lunar research
- Identifying unusual mineralogical features
- Validating spectral classification models

## Team Members
- Ridham Vijaybhai Patel
- Kandarp Dipakkumar Gajjar
- Krutika Vijaybhai Patel
- Nancy Rajesh Patel

## Institution
LDRP Institute of Technology and Research, Gandhinagar (KSV)
