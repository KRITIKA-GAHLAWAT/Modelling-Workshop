# Breast Cancer Diagnosis Using Statistical Neural Networks

##  Overview
Breast cancer is one of the leading causes of cancer-related deaths among women.  
This project implements **Statistical Neural Networks** for **breast cancer diagnosis**,  
using machine learning models to classify tumors as **benign** or **malignant**.

###  Key Features

- **Dataset**: University of Wisconsin Breast Cancer Database (699 samples, 9 attributes).
- **Machine Learning Models**:
  - **Radial Basis Function (RBF) Network** – A curve-fitting approach for pattern recognition.
  - **Probabilistic Neural Network (PNN)** – A Bayesian classifier for precise probability estimation.
  - **General Regression Neural Network (GRNN)** – A kernel regression model for function approximation.
- **Performance Evaluation**: Accuracy, Sensitivity, Specificity, ROC Curve.

##  Dataset Information

The dataset contains **9 cell-based attributes**, each rated from **1 to 10**:

1. Lump Thickness
2. Uniformity of Cell Size
3. Uniformity of Cell Shape
4. Marginal Adhesion
5. Single Epithelial Cell Size
6. Bare Nuclei
7. Bland Chromatin
8. Normal Nucleoli
9. Mitoses (Cell Growth Rate)

The classification labels:
- **Benign (Non-Cancerous)**
- **Malignant (Cancerous)**

##  Installation

Clone the repository:

```bash
git clone https://github.com/your-repo/breast-cancer-diagnosis.git
cd breast-cancer-diagnosis
