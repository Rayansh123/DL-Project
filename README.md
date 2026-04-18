# Visual Forensics of Synthetic Faces
**Fusing Spatial, Spectral, and Structural Domains**

This repository contains the implementation of a Multi-Stream Fusion Network for Deepfake detection, achieving **97.59% accuracy**.

### Key Features
* **Tri-Domain Analysis:** Combines RGB Textures (Spatial), FFT Frequency Heatmaps (Spectral), and Facial Landmarks (Structural).
* **Explainable AI:** Includes an ablation study proving that modern GANs have rendered structural heuristics obsolete (contributing <0.1% to decision-making).

### Files
* `DL-Project.ipynb`: Full data pipeline and training code.
* `best_tristream.pth`: Trained model weights.
* `train_with_landmarks_10k.csv`: Preprocessed dataset metadata.
* `test_with_landmarks_2k.csv`: Preprocessed dataset metadata.
