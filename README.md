# Breast Cancer Classification

This project is a web-based application that classifies breast cancer as either **benign** or **malignant** using diagnostic metrics derived from the Breast Cancer Wisconsin dataset. The model runs in the browser using TensorFlow.js, providing an interactive tool for health specialists to assess breast cancer risk.

## Model Overview

The model processes 30 features derived from diagnostic tests, which are grouped into three categories:

- **Mean Features:** Average measurements of cell nuclei characteristics (e.g., Radius, Texture, Perimeter).
- **Standard Error (SE) Features:** Variability in the measurements, indicating how consistent the diagnostic tests are.
- **Worst Features:** The most extreme measurements, which can be critical in highlighting abnormal cell characteristics.

Based on these metrics, the model classifies the input as either **benign** or **malignant**.

## Performance Metrics

The model has achieved the following performance on a validation/test dataset:

- **Precision:** 0.9858  
- **Recall:** 0.9858  
- **F1 Score:** 0.9858  

### Confusion Matrix
[[354 3]

[ 3 209]]

- **True Negatives:** 354  
- **False Positives:** 3  
- **False Negatives:** 3  
- **True Positives:** 209  

These metrics indicate that the model performs with high accuracy, making it a reliable tool for assisting in breast cancer diagnosis.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, etc.)
- Internet connection to load TensorFlow.js from a CDN
