<p align="center">
  <img src="images/your-banner-file-name.png" width="100%">
</p>
# Clustering Penguins – Unsupervised Machine Learning

## Overview
This project applies **K-Means clustering** to the Palmer Penguins dataset 
using numeric morphological features.

The objective is to:
- Perform unsupervised clustering
- Compare results before and after feature scaling
- Evaluate how closely clusters align with true species

---

## Dataset Features Used

- bill_length_mm
- bill_depth_mm
- flipper_length_mm
- body_mass_g

Note: The species column is NOT used for training (unsupervised learning).
It is only used for evaluation.

---

## Methods Applied

### 1. Baseline K-Means (No Scaling)

### 2. Standardisation (Z-score scaling)
Using `StandardScaler`

### 3. Normalisation (Min-Max scaling)
Using `MinMaxScaler`

### 4. PCA Visualisation
2D dimensionality reduction for cluster visualisation

---

## Evaluation Metric

Adjusted Rand Index (ARI)

- 1 = perfect agreement
- 0 = random clustering

---

## Key Findings

- Distance-based algorithms require scaling.
- Standardisation improves clustering stability.
- Body mass and flipper length are strong separating features.
- PCA provides interpretable 2D visualisation.

---

## Repository Structure
