# 🚀 100 Days of Machine Learning & Custom Code Implementations

Welcome to the **100 Days of Machine Learning** repository! This repository combines a structured curriculum of Machine Learning theory, math, code from scratch, and custom-designed Jupyter Notebooks complete with interactive visualizations and clean data preprocessing workflows.

---

## 📌 Repository Overview

This repository integrates core machine learning concepts ranging from basic data preprocessing to advanced ensemble models and end-to-end projects:

- **Theoretical Foundations**: Detailed math explanations and markdown summaries.
- **Custom Notebooks**: Visually styled Jupyter Notebooks (`Machine Code`) with custom linear-gradient styling, step-by-step code execution, and data analysis.
- **Hands-on Projects**: End-to-end Machine Learning pipelines on real-world datasets (`sonar data`, `Diabetes`, `500hits`).

---

## 📂 Repository Structure

### 1️⃣ Data Preprocessing & Feature Engineering
- [`day24-standardization`](./day24-standardization/) — Feature Scaling via Standardization (`Z-Score`). Includes [`Feature_Scaling_Normalization_vs_Standardization.ipynb`](./day24-standardization/Feature_Scaling_Normalization_vs_Standardization.ipynb).
- [`day25-normalization`](./day25-normalization/) — Normalization (`MinMaxScaling`).
- [`day26-ordinal-encoding`](./day26-ordinal-encoding/) — Ordinal & Label Encoding.
- [`day27-one-hot-encoding`](./day27-one-hot-encoding/) — One Hot Encoding using Scikit-Learn. Includes [`One_Hot_Encoder_Scikit_Learn.ipynb`](./day27-one-hot-encoding/One_Hot_Encoder_Scikit_Learn.ipynb).
- [`day28-column-transformer`](./day28-column-transformer/) — Pipelines & `ColumnTransformer`. Includes [`Column_Transformer.ipynb`](./day28-column-transformer/Column_Transformer.ipynb).
- [`day36-imputing-numerical-data`](./day36-imputing-numerical-data/) — Handling missing data using [`Simple_Imputer.ipynb`](./day36-imputing-numerical-data/Simple_Imputer.ipynb).
- [`day39-knn-imputer`](./day39-knn-imputer/) — Missing value imputation using KNN.

### 2️⃣ Supervised Learning Algorithms & Models
- [`day48-simple-linear-regression`](./day48-simple-linear-regression/) — Simple Linear Regression from scratch.
- [`day50-multiple-linear-regression`](./day50-multiple-linear-regression/) — Multiple Linear Regression.
- [`day51-gradient-descent`](./day51-gradient-descent/) — Gradient Descent from scratch (2D & 3D visualizations).
- [`day58-logistic-regression`](./day58-logistic-regression/) — Logistic Regression & Perceptron Trick. Includes [`Logistic_Regression.ipynb`](./day58-logistic-regression/Logistic_Regression.ipynb).
- [`knn-classification`](./knn-classification/) — K-Nearest Neighbors Classification using [`KNN.ipynb`](./knn-classification/KNN.ipynb).
- [`support-vector-machines`](./support-vector-machines/) — Support Vector Machine classification & hyperparameter tuning with [`Support_Vector_Machines.ipynb`](./support-vector-machines/Support_Vector_Machines.ipynb) and [`Ml_svm.ipynb`](./support-vector-machines/Ml_svm.ipynb).
- [`decision-trees`](./decision-trees/) — Decision Trees classification & tree visualization using [`Decision_Tree.ipynb`](./decision-trees/Decision_Tree.ipynb).
- [`day65-random-forest`](./day65-random-forest/) — Bagging & Random Forest classifiers.
- [`day66-adaboost`](./day66-adaboost/) — AdaBoost Boosting algorithm.
- [`gradient-boosting`](./gradient-boosting/) — Gradient Boosting step-by-step.
- [`kmeans`](./kmeans/) — K-Means Unsupervised Clustering & Streamlit application.

### 3️⃣ Model Evaluation & Selection
- [`train-test-split`](./train-test-split/) — Train-Test Splitting & Data Partitioning (`Train_Test_Split.ipynb`).
- [`cross-validation`](./cross-validation/) — K-Fold & Stratified Cross-Validation (`Cross_Validation.ipynb`).
- [`day49-regression-metrics`](./day49-regression-metrics/) — MAE, MSE, RMSE, R2 Score.
- [`day59-classification-metrics`](./day59-classification-metrics/) — Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC.

### 4️⃣ Machine Learning Projects
- [`ml-projects/project-1`](./ml-projects/project-1/) — End-to-End Machine Learning Projects featuring datasets:
  - `sonar data.csv` (Rock vs Mine Classification)
  - `Diabetes_T.csv` (Diabetes Outcome Prediction)
  - `500hits.csv` (Baseball Hits Classification)

---

## ⚙️ Installation & Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/100-Days-Of-Machine-Learning-Complete.git
   cd 100-Days-Of-Machine-Learning-Complete
   ```

2. **Set up Virtual Environment**:
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter streamlit
   ```

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

---

## 👤 Author & Acknowledgments

- **Author**: Vicky Raj
- **Curriculum & Core Concepts**: Inspired by 100 Days of Machine Learning & Custom ML Code Experiments.
