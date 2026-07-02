# Breast Cancer Wisconsin (Original) Disease Prediction

## Project Overview

This project uses machine learning techniques to predict whether a breast tumor is **benign** or **malignant** based on patient medical measurements from the Breast Cancer Wisconsin (Original) dataset.

The objective is to build and compare classification models that assist in the early detection of breast cancer using structured medical data.

---

## Dataset

**Dataset Name:** Breast Cancer Wisconsin (Original)

**Source:** UCI Machine Learning Repository

The dataset contains samples collected from breast mass examinations. Each record consists of several cytological features obtained from fine needle aspiration (FNA) of breast tissue.

### Features

- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Marginal Adhesion
- Single Epithelial Cell Size
- Bare Nuclei
- Bland Chromatin
- Normal Nucleoli
- Mitoses

### Target Variable

- **2** → Benign
- **4** → Malignant

---

## Project Objectives

- Predict breast cancer diagnosis using machine learning.
- Compare multiple classification algorithms.
- Evaluate model performance using standard metrics.
- Identify the best-performing model for prediction.

---

## Machine Learning Algorithms

The following algorithms can be implemented:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- XGBoost (Optional)
- K-Nearest Neighbors (Optional)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost 
- Jupyter Notebook 

---

## Project Workflow

1. Load the dataset.
2. Explore the data.
3. Handle missing values.
4. Encode the target variable.
5. Normalize or standardize features (if required).
6. Split the data into training and testing sets.
7. Train multiple machine learning models.
8. Evaluate model performance.
9. Compare results.
10. Predict breast cancer diagnosis.

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Installation

Clone the repository:

```bash
git clone https://github.com/BEGINNERUSER-git/codealpha_tasks.git
```

Navigate to the project folder:

```bash
cd task2
```

Install the required packages:

```bash
pip install -r requirement.txt
```

---

## Running the Project

Run the Jupyter Notebook:

```bash
jupyter notebook
```
---

## Expected Output

The trained model predicts whether a tumor is:

- Benign
- Malignant

The project also displays:

- Confusion Matrix
- Classification Report
- ROC Curve
- Accuracy Score

---

## License

This project is intended for educational and research purposes.