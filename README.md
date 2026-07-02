# Hybrid_Navarasa_FER

## A Global--Local Hybrid Transformer Framework for Automatic Navarasa Facial Expression Recognition

**Authors**

-   Varun Chand H
-   Tien Anh Tran
-   Pravinkumar M Sonsare
-   Ananda Resmi S
-   Pratik Agrawal
-   Mehdi Gheisari

## Overview

This repository contains the complete reproducible workflow accompanying
the manuscript **"A Global--Local Hybrid Transformer Framework for
Automatic Navarasa Facial Expression Recognition."**

The proposed framework combines global semantic representations
extracted using a Vision Transformer (ViT) and local spatial
representations extracted using a Swin Transformer. The extracted
features are fused using feature concatenation and classified with a
lightweight multilayer perceptron (MLP).

The repository has been organized into separate Jupyter notebooks to
improve transparency and reproducibility.

## Repository Highlights

• Complete end-to-end reproducible workflow
• Modular Jupyter notebooks for each experimental stage
• Vision Transformer (ViT) and Swin Transformer feature extraction
• Hybrid feature fusion using an MLP classifier
• Comprehensive evaluation metrics
• Statistical significance analysis (McNemar's test and Bootstrap confidence intervals)
• Explainable AI using Grad-CAM
• Ablation study of the proposed architecture

## Repository Structure

``` text
Hybrid_Navarasa_FER/
│
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Feature_Extraction.ipynb
│   ├── 03_Hybrid_Model_Training.ipynb
│   ├── 04_Model_Evaluation.ipynb
│   ├── 05_Statistical_Analysis.ipynb
│   ├── 06_GradCAM_Explainability.ipynb
│   └── 07_Ablation_Study.ipynb
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── CITATION.cff
```

## Dataset

The experiments use the publicly available Navarasa Facial Expression
Recognition dataset:

https://www.kaggle.com/datasets/pranay15nath/navarasa-fer

The experiments were conducted using the publicly available Navarasa Facial Expression Recognition dataset available on Kaggle. After downloading the dataset, users should organize the images into training, validation, and testing directories as described in the preprocessing notebook.

## Software Requirements

-   Python 3.11
-   Google Colab
-   NVIDIA Tesla T4 GPU (used for experiments)

## Notebook Execution Order

1.  Data Preprocessing
2.  Feature Extraction
3.  Hybrid Model Training
4.  Model Evaluation
5.  Statistical Analysis
6.  Grad-CAM Explainability
7.  Ablation Study

Run the notebooks sequentially.

## Outputs

The workflow generates:

-   Extracted feature vectors
-   Trained evaluation results
-   Performance metrics
-   Confusion matrices
-   ROC curves
-   Statistical analysis results
-   Grad-CAM visualizations
-   Ablation study tables

## Reproducibility

This repository provides the complete experimental workflow used in the
manuscript.

**Note:** Trained model weights are not included in this repository.
Users should execute the notebooks sequentially to reproduce the
reported workflow and analyses.

## Citation

If you use this repository, please cite the associated publication. The complete citation will be updated once the article is published.

## License

This repository is distributed under the MIT License.

## Contact

For questions regarding the repository or the implementation, please contact the corresponding author using the contact information provided in the published article.

## Acknowledgement

The authors gratefully acknowledge the developers of PyTorch, TIMM, scikit-learn, OpenCV, and the creators of the publicly available Navarasa FER dataset.
