# Audio Clustering Analysis

## Overview
This project performs unsupervised clustering on unlabeled audio files using extracted audio features and dimensionality reduction techniques.

## Features
- **Audio Feature Extraction**: Extracts mel spectrogram and spectral features from WAV files using librosa
- **Dimensionality Reduction**: Applies PCA and t-SNE for visualization and clustering
- **Clustering Methods**: K-means and DBSCAN clustering algorithms
- **Visualization**: 2D/3D scatter plots and cluster analysis

## Key Files
- Feature extraction from audio files
- Elbow method for optimal cluster selection
- Comparative analysis of PCA vs t-SNE for cluster separability
- Interactive visualizations of clustering results

## Requirements
```
librosa
sklearn
matplotlib
seaborn
numpy
pandas
```

## Usage
1. Place audio files in `/content/unlabelled_sounds/unlabelled_sounds/`
2. Run feature extraction notebook
3. Apply clustering algorithms
4. Visualize results with dimensionality reduction

## Results
t-SNE provides superior cluster separability compared to PCA for this audio dataset, revealing 3-4 distinct clusters with clear boundaries.
