# Multimodal Fusion Framework for Accurate Insomnia Detection

This repository contains the implementation of a **Multimodal Fusion Deep Learning Framework** for detecting insomnia using biosignals like EEG, ECG, EMG, and EOG. The aim is to leverage the power of early and late fusion strategies to improve insomnia detection performance using both raw and handcrafted features, attention mechanisms, and explainability methods.

## 🧠 Project Overview

Insomnia is a common sleep disorder that affects millions globally. Biosignals such as EEG, ECG, EOG, and EMG provide vital information for assessing sleep quality. This project proposes a deep learning-based multimodal architecture that combines these signals using fusion strategies to enhance classification performance.

The framework integrates:
- **Preprocessing** and **normalization** of raw signals.
- **Early Fusion**: Combines features at the input level.
- **Late Fusion**: Integrates decisions from multiple unimodal branches.
- **Attention-based Fusion (BSP-ATT)**: Learns signal importance weights.
- **XAI (Explainable AI)**: Visual explanations to interpret model predictions.

## 📂 Repository Structure

| File/Folder | Description |
|------------|-------------|
| `BSP_1.ipynb` | Baseline single-modal models for each biosignal. |
| `BSP_1_EarlyFusion.ipynb` | Early fusion model integrating multimodal features. |
| `BSP_1_LateFusion.ipynb` | Late fusion strategy combining model outputs. |
| `BSP-ATT.ipynb` | Attention-based fusion architecture. |
| `BSP_XAI.ipynb` | Explainable AI visualizations and saliency maps. |
| `Norm_BSP_1_EarlyFusion.ipynb` | Early fusion model using normalized data. |
| `combined_data.xlsx` | Dataset containing preprocessed multimodal features. |
| `csv_output/` | Folder for CSV prediction/logging outputs. |
| `README.md` | Project documentation (this file). |

## 🔧 Requirements

- Python 3.8+
- TensorFlow / PyTorch (depending on notebook)
- NumPy, Pandas, Matplotlib
- SciPy
- scikit-learn
- XAI libraries (e.g., SHAP and LIME)

