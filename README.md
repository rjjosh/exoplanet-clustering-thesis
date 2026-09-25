# Exoplanet Clustering Thesis
Machine learning analysis of exoplanet population structure and discovery bias using NASA Exoplanet Archive data.


This repository contains the code and analysis used for my Master's thesis on exoplanet population structure and discovery-method bias using data from the NASA Exoplanet Archive.

## Thesis Topic

The research investigates whether machine-learning-discovered exoplanet groups represent real physical population regimes or whether they are strongly influenced by discovery-method biases and selection effects.

## Research Questions

1. Are groups of planets found using machine learning real physical groups, or are they influenced by biases and selection effects in the discovery methods?

2. Does the low-density space between population clusters reflect natural planetary formation constraints or telescope detection effects?

## Dataset

The analysis uses data from the NASA Exoplanet Archive.

The dataset snapshot used in this thesis was downloaded on 16 February 2026.

Raw dataset:
- 39,386 rows
- 92 columns

After filtering using `default_flag = 1`:
- 6,107 confirmed exoplanets

## Main Analysis

The analysis includes:

- Data cleaning and preprocessing
- Missing-value analysis
- Median imputation
- Log transformation
- Standardization
- Principal Component Analysis (PCA)
- K-Means clustering
- Gaussian Mixture Models
- Hierarchical clustering
- HDBSCAN
- Silhouette analysis
- Adjusted Rand Index
- Chi-square test
- Cramer's V
- Bootstrap stability analysis
- Sensitivity analysis
- KDE density analysis
- Dip test
- Gaussian-copula null simulation

## Main Notebook

The main analysis is contained in:

`exoplanet_thesis_final.ipynb`

## Reproducibility

The notebook contains the code used to generate the numerical results, tables, and figures reported in the thesis.

## Author

Rajesh Joshi

Master's Thesis, 2026
