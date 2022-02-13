# Multiscale COVID-19

## Multiscale Analysis of COVID-19 (MOAC) Spatiotemporal Variations

### 1. Overview
#### This project develops a multiscale optimization engineering approach to perform the following tasks:

- To model and forecast the growth (G-rate) in the number of confirmed COVID-19 cases and the associated death rates (D-rate) from the global to continental scales 
- To identify the optimal control measures at the same spatial scales till indiviudal country-level via explainable deep learning with SHAP and clustering analysis

#### In this repository, we share the code and data for our above proposed tasks as part of the Multiscale Optimization Analysis of COVID-19 (MOAC) Spatiotemporal Variations.

### 2. Data Description

Please refer to our shared data folder for information of the datasets (before and after data processing) to perform the above tasks.

### 3. Workflow

Building upon the collated datasets, our proposed analysis for MOAC consists of multi-stage systematic analyses, as depicted in Fig. 1, which are defined as follows:

##### Stage A: Data Processing
- This stage focuses on processing the original raw datasets (see "Raw" folder in above shared data folder) to generate processed data (in .h5 format) for the global and respective continental scales.
- Refer to respective Jupyter Notebooks titled as "Stage A_Data processing into HDF5 data format (Global scale)" and "Stage A_Data processing into HDF5 data format (Continental scale)".

##### Stage B: Predictive Modelling

##### Stage C: SHAP Analysis

##### Stage D: Data Visualizations

##### Stage E: Near Real-Time Deployment

![Proposed workflow](https://user-images.githubusercontent.com/70025024/153757221-13dec56a-a0ac-4d12-a8f1-320e38b086ca.svg)
Fig. 1. Stages involved in proposed workflow for MOAC

### 4. Installation
