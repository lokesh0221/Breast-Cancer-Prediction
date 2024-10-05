# Breast Cancer Prediction

## Overview

This project predicts whether breast cancer is benign or malignant based on the patient's medical data. It uses the Support Vector Machine (SVM) algorithm with feature selection and polynomial feature transformation for better accuracy.

## Dataset

The dataset used for this project contains the following:

- **ID**: Unique identifier for each patient (dropped during preprocessing).
- **Diagnosis**: Target variable representing if cancer is malignant (M) or benign (B).
- **30 Features**: Numeric features derived from imaging data of breast cells.

## Installation

To run the project, install the required libraries by executing:

```bash
pip install pandas scikit-learn
