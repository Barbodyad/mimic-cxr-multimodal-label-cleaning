# mimic-cxr-multimodal-label-cleaning
Multimodal Chest X-Ray Classification with Label Noise Correction on MIMIC-CXR

# Multimodal Chest X-Ray Classification with Label Noise Correction

[![Paper](https://img.shields.io/badge/Paper-DATA%202026-blue)](https://doi.org/10.5220/0015230100004091)

Official code for **"Toward Reliable Automated Radiography: Improving Chest X-Ray Diagnosis through Multimodal Fusion and Label Cleaning"**, published at DATA 2026.

📄 Paper: https://doi.org/10.5220/0015230100004091

## Paper
**"Multimodal Chest X-Ray Classification with Automated Label Noise Correction on MIMIC-CXR"**  
Barbod Yad, Department of Computer Science  
*published to DATA 2026*

## Overview
- EfficientNet-B3 for image classification
- Bio_ClinicalBERT for radiology report text encoding
- Confidence-threshold label noise correction
- Evaluated on MIMIC-CXR dataset

## Dataset
MIMIC-CXR v2.0 — requires PhysioNet credentialed access:  
https://physionet.org/content/mimic-cxr/

## Requirements
torch, torchvision, transformers, scikit-learn, pandas, numpy, matplotlib, Pillow

## Usage
Run on Kaggle with GPU T4 x2:
1. Add mimic-cxr-dataset and mimic-cxr-official-csv
2. Open mimic_multimodal_clean.ipynb
3. Run All
