# Proximity Ligation Assay (PLA) Nuclear Analysis Pipeline

## Overview
The **Proximity Ligation Assay (PLA)** is a powerful method for detecting protein-protein interactions with high specificity and sensitivity. This example data is using oligonucleotide-labeled antibodies, this technique enables the visualization of molecular interactions in cells via fluorescence microscopy. The signal is amplified using **Hybridization Chain Reaction (HCR)**, providing robust detection of nuclear interactors.

This repository contains a **Python-based Jupyter Notebook pipeline** for analyzing nuclear PLA signals, specifically tailored for **PLA** data. The analysis is designed to process fluorescence microscopy images, extract nuclear signal distributions, and generate quantifiable outputs for interaction studies.

## Authors
Developed by **Julian Zagalak**, based on an excellent primer by **Stefania Marcotti**: [Introduction to Image Analysis](https://github.com/RMS-DAIM/introduction-to-image-analysis).

## Pipeline Description
The **PLA Nuclear Analysis Pipeline** provides:
- **Preprocessing of input images**: Converts raw microscopy images into an analyzable format, normalizing intensity values and removing background noise.
- **Segmentation and feature extraction**: Identifies nuclear regions and quantifies PLA signal intensities within these compartments.
- **Data structure manipulation**: Outputs structured results, including CSV tables with nuclear interaction metrics and visualization overlays for signal localization.
- **Statistical analysis & visualization**: Generates plots and summaries to compare interaction patterns across conditions.

## Example Data
Example dataset: **Hybridization Chain Reaction (HCR) - PLA signal detection of nuclear interactors**.
Experimental data (fluorescence microscopy images in TIFF) can be found in the data folder segregated into treatment groups (Well1, Well2, Well3, etc)
Python scripts are to be found in the Scripts/Jupyter folder. Open/Run Nuclear_Intensity_batch-V2.ipynb in Jupyter notebook to process TEST data set
