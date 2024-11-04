# Evolving Support Vector Machines with Fruit Fly Optimization for Medical Data Classification

This repository contains my implementation of the following research article:

**"Evolving Support Vector Machines Using Fruit Fly Optimization for Medical Data Classification"**

- **Authors**: Liming Shen, Huiling Chen, Zhe Yu, Wenchang Kang, Bingyu Zhang, Huaizhong Li, Bo Yang, Dayou Liu
- **Published in**: *Knowledge-Based Systems*, Volume 96, 2016, Pages 61-75
- **DOI**: [10.1016/j.knosys.2016.01.002](https://doi.org/10.1016/j.knosys.2016.01.002)

---

## Overview

This project applies the **Fruit Fly Optimization Algorithm (FOA)** to tune parameters of the **Support Vector Machine (SVM)** for improved classification accuracy in medical data. The FOA-SVM approach optimizes SVM parameters to enhance classification performance on medical diagnosis datasets, including Parkinson’s disease and thyroid disease.

The implementation includes:
- **Parameter Optimization**: Using FOA to dynamically adjust the penalty parameter `C` and kernel parameter `γ` of SVM.
- **Medical Dataset Classification**: Applying FOA-SVM on well-known medical datasets to classify cases with high accuracy and efficiency.

## Methodology

The project follows the FOA-SVM method outlined in the article:
1. **Fruit Fly Optimization Algorithm (FOA)**: This biologically-inspired algorithm simulates the foraging behavior of fruit flies to find optimal SVM parameters.
2. **Support Vector Machine (SVM)**: The optimized SVM model is used to classify medical datasets with high accuracy by maximizing the margin between classes.

## Datasets

The implementation is evaluated on four benchmark medical datasets as specified in the paper:
- **Wisconsin Breast Cancer Dataset**
- **Pima Indians Diabetes Dataset**
- **Parkinson’s Disease Dataset**
- **Thyroid Disease Dataset**

These datasets are preprocessed and scaled to ensure that the FOA-SVM method can efficiently optimize the model's performance.

## Requirements

To run this implementation, you need:
- Python 3.x
- Libraries: `numpy`, `scikit-learn`, `matplotlib` (for visualization)
