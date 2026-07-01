# Data and Code Availability

## Data Availability

The experiments presented in this repository use the **Navarasa Facial Expression Recognition (FER)** dataset, which is publicly available on Kaggle:

https://www.kaggle.com/datasets/pranay15nath/navarasa-fer

The dataset is **not redistributed** in this repository. Users should download it directly from the original source and organize it into the required training, validation, and testing directories before executing the notebooks.

---

## Code Availability

This repository provides the complete implementation workflow accompanying the manuscript:

**A Global–Local Hybrid Transformer Framework for Automatic Navarasa Facial Expression Recognition**

The implementation is organized into seven modular Jupyter notebooks:

1. Data Preprocessing
2. Feature Extraction
3. Hybrid Model Training
4. Model Evaluation
5. Statistical Analysis
6. Grad-CAM Explainability
7. Ablation Study

The notebooks are intended to be executed sequentially to reproduce the complete experimental workflow.

---

## Trained Models

To keep the repository lightweight and easy to distribute, pretrained model weights are **not included**.

Users can reproduce the reported workflow by executing the notebooks in sequence after preparing the dataset and installing the required dependencies.

---

## Reproducibility

The repository has been organized to improve transparency and reproducibility by separating each stage of the proposed framework into an independent notebook.

All software dependencies are listed in `requirements.txt`.

The repository is intended to support independent verification of the methodology described in the accompanying manuscript.

---

## Hardware and Software

The reported experiments were conducted using:

- Python 3.11
- Google Colab
- NVIDIA Tesla T4 GPU

Equivalent or newer hardware/software configurations should also be suitable.

---

## Journal Statement

**Suggested manuscript statement**

> The source code supporting this study is publicly available through the accompanying GitHub repository. The implementation is organized into modular Jupyter notebooks covering data preprocessing, feature extraction, hybrid model training, evaluation, statistical analysis, explainability, and ablation study. The Navarasa FER dataset used in this work is publicly available on Kaggle and can be obtained from the original source. Trained model weights are not distributed with the repository.
