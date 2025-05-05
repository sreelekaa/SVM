# Support Vector Machine (SVM) Classification Project

This project demonstrates how to use Support Vector Machines (SVM) for both **linear** and **non-linear classification** using Scikit-learn, NumPy, and Matplotlib.

## 🔧 Tools Used
- Python
- Scikit-learn
- NumPy
- Matplotlib

## 📊 Dataset
The **Breast Cancer dataset** from Scikit-learn is used. For visualization, only the first two features are selected.

## 📌 Objectives
- Load and prepare a dataset for binary classification.
- Train SVM with linear and RBF kernels.
- Visualize the decision boundaries.
- Tune hyperparameters like `C` and `gamma`.
- Evaluate performance using cross-validation.

## 🧠 Key Concepts
- **Support Vectors**: Data points closest to the decision boundary.
- **Hyperplane**: The boundary that separates classes.
- **Margin**: Distance between support vectors and the hyperplane.
- **Kernel Trick**: Technique to separate non-linearly separable data by transforming it to a higher dimension.

## 🚀 How to Run

1. Clone the repository or copy the code into a Python file or Jupyter Notebook.

2. Install dependencies:
    ```bash
    pip install scikit-learn numpy matplotlib
    ```

3. Run the script:
    ```bash
    python SVM.py
    ```

## 📈 Output
- Decision boundaries for both linear and RBF kernel SVMs.
- Cross-validation accuracy.
- Best parameters found using GridSearchCV.



