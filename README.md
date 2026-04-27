## IDx-DR: Diabetic Retinopathy Detection
## Reproducible AI for Diabetic Retinopathy Screening – Inspired by IDx-DR

## Project Overview
This repository contains a reproducible deep learning model for detecting referable diabetic retinopathy (moderate or worse) from fundus images. The model uses transfer learning with EfficientNet-B4 and achieves >85% sensitivity and specificity on the APTOS 2019 dataset.This project implements a deep learning model using EfficientNet-B4 to detect referable diabetic retinopathy from retinal fundus images, following the clinical validation standards of systems like IDx-DR.

## Quick Start
[![Open In Colab](https://drive.google.com/drive/folders/1srDD27GNJT-9TPEn-kdSN7N_fQORdF1u?usp=sharing)](https://colab.research.google.com/drive/1rQ9fAJJijdHPQi4GWHkJt02swaAd4kSF?usp=sharing)

## Clinical Background
Diabetic Retinopathy (DR) is a leading cause of blindness. Autonomous AI systems like IDx-DR (FDA cleared) provide binary "refer/no refer" outputs to increase screening accessibility.

## Model Performance
- Dataset: APTOS 2019 Blindness Detection
- Architecture: EfficientNet-B4
- Target: Binary Classification (Referable vs. Non-referable DR)

## Repository Structure
- `DR_Detection_IDx_APTOS2019.ipynb`: Main training and evaluation notebook
- `requirements.txt`: Environment dependencies
- `README.md`: Project documentation

## References
- Abràmoff et al. (2018). NPJ Digital Medicine.
- FDA DEN180001
- APTOS 2019 Dataset (Kaggle)
