# PCA Dimensionality Reduction on Digits Dataset

## Project Overview

This project demonstrates the use of Principal Component Analysis (PCA), an unsupervised machine learning technique used for dimensionality reduction.

The original digits dataset contains 64 features representing 8×8 pixel images of handwritten digits. PCA is applied to reduce the number of features while preserving most of the information in the data.

---

## Objectives

- Understand Principal Component Analysis (PCA)
- Reduce high-dimensional data into fewer dimensions
- Visualize data using principal components
- Determine the optimal number of components
- Retain 95% of the original variance

---

## Dataset

Source: Scikit-Learn Digits Dataset

- Samples: 1797
- Features: 64
- Classes: 10 (Digits 0–9)

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## Project Workflow

1. Load Digits Dataset
2. Data Exploration
3. Feature Standardization
4. Apply PCA with 2 Components
5. Visualize PCA Projection
6. Calculate Explained Variance
7. Find Components Required for 95% Variance
8. Apply PCA with Optimal Components
9. Interpret Results

---

## Results

- Original Features: 64
- Reduced Features: 40
- Variance Retained: 95%

PCA successfully reduced dimensionality while preserving most of the information.

---

## Key Learnings

- Principal Components
- Explained Variance Ratio
- Cumulative Variance
- Feature Extraction
- Dimensionality Reduction

---

## Visualizations

- PCA Scatter Plot
- Explained Variance Curve
- Top Principal Components

---

## Author

Dipak Chaudhari