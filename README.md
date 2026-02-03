# Multi-retinal Disease Detection

Transfer learning for multi-label retinal disease classification using deep learning.

This project focuses on automated detection of three major retinal diseases:
- **Diabetic Retinopathy (DR)**
- **Glaucoma (G)**
- **Age-related Macular Degeneration (AMD)**

The work was conducted as a final project for a Deep Learning course and explores advanced techniques for medical image classification under limited-data settings.

---

## Overview

Medical image datasets are often small and expensive to label. To address this challenge, this project applies **transfer learning** using pretrained convolutional neural networks and fine-tuning strategies to improve performance on multi-label retinal disease detection.

The experiments are conducted on the **ODIR dataset**, with images resized to 256×256 resolution. Performance is evaluated using precision, recall, and F1-score for each disease, as well as the average F1-score across diseases.

---

## Implemented Tasks

### Task 1 – Transfer Learning
- Fine-tuning pretrained **ResNet18** and **EfficientNet** models
- Comparison of different fine-tuning strategies

### Task 2 – Loss Functions
- **Focal Loss**
- **Class-Balanced Loss**
- Performance comparison under class imbalance

### Task 3 – Attention Mechanisms
- Squeeze-and-Excitation (SE)
- Multi-Head Attention (MHA)
- Trained attention-based models are provided via GitHub Releases

### Task 4 – Ensemble Methods
- Max voting
- Weighted ensemble
- Stacking
- Adaptive ensemble strategies
- Test-time augmentation (TTA)

---

## Repository Structure
models/
task1/        # Trained models for Task 1
task2/        # Trained models for Task 2
task3/        # Attention models (released separately)

notebooks/
main dl code.ipynb   # Main training and evaluation notebook

outputs/
task4/        # CSV results for ensemble experiments

reports/
DLsns_technique_report.pdf

src/
(reserved for future modular code)
---

## Trained Models

- Task 1 and Task 2 models are stored under the `models/` directory.
- **Task 3 attention models** are provided via **GitHub Releases** due to file size limitations.

---

## Notes

- This repository is intended for **academic reference and portfolio demonstration**.
- The code and models are provided as-is.
- Dataset files are not included due to licensing restrictions.

---

## License & Usage

**Copyright © 2026 Sahar Fatemi**

All rights reserved.

This repository and its contents, including source code, trained models, notebooks, reports, and output files, are protected by copyright law.

No part of this repository may be used, copied, modified, distributed, or incorporated into derivative works without explicit written permission from the copyright holder.

This work is provided for viewing and academic reference only.
