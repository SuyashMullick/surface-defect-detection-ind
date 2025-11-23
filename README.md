# surface-defect-detection-ind

This project implements an end-to-end anomaly detection pipeline for industrial surface inspection using the MVTec Anomaly Detection (AD) dataset. It combines classical computer vision, deep learning autoencoders, and feature-embedding methods like PaDiM to detect subtle defects across multiple object categories.

## 🚀 Features

### MVTec AD dataset integration
Structured loaders for all 15 object and texture categories.

### Classical CV baselines
Traditional image processing techniques for quick, interpretable benchmarks.

### Autoencoder-based anomaly detection
Pixel-level reconstruction error for detecting irregularities.

### PaDiM (Patch Distribution Modeling)
Embedding extraction from pretrained backbones and multivariate Gaussian modeling for high-quality anomaly maps.

### Evaluation metrics
Supports ROC-AUC, pixel-AUC, and visualization of anomaly heatmaps.

### Modular pipeline
Easy to extend with new models or feature extractors.
