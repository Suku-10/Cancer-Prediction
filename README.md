# Breast Cancer Classification with SVM

## Overview
This project demonstrates the use of a **Support Vector Machine (SVM)** classifier with a radial basis function (RBF) kernel to classify tumors from the Breast Cancer Wisconsin dataset as malignant or benign. The dataset is provided by `scikit-learn`, and the project focuses on visualizing the decision boundary using only two features: `mean radius` and `mean texture`.

## Objective
- Train an SVM classifier on a subset of the breast cancer dataset.
- Visualize the decision boundary to illustrate how the model separates malignant (0) and benign (1) tumors in a 2D feature space.

## Dataset
- **Source**: `sklearn.datasets.load_breast_cancer`
- **Features Used**: 
  - `mean radius` (feature 0)
  - `mean texture` (feature 1)
- **Target**: Binary classification (0 = malignant, 1 = benign)
- **Size**: 569 samples, 2 features (subset of the full 30-feature dataset)

## Installation:- 
1. Clone the repository:
   ```bash
   git clone https://github.com/Suku-10/Cancer-Prediction.git
   cd Cancer-Prediction

2. Create Virtual Enviornment:
    ```bash
    python -m venv myenv
    myenv\scripts\activate

3. Install dependencies:
    ```bash
    pip install -r requirements.txt

4. Open the Jupyter Notebook:
    ```bash 
    jupyter notebook SVM_Cancer.ipynb


## Results:- 

A 2D plot is generated, showing:
- The decision boundary (colored regions) separating malignant and benign classes.
- Data points overlaid with colors indicating their true labels (e.g., red for malignant, blue for benign).
- The RBF kernel creates a non-linear boundary, demonstrating SVM’s ability to handle complex data patterns.