# Breast Cancer Classification using KNN, Logistic Regression, SVM, and Ensemble Methods

## Project Overview
This project explores and evaluates multiple classification algorithms, including K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVM), and ensemble methods (Boosting and Bagging), using the Breast Cancer dataset. The goal is to classify tumor diagnoses as malignant or benign and analyze model performance comprehensively.

## Dataset Information
The dataset consists of 567 samples with 30 features, including:
- radius_mean
- texture_mean
- concavity_mean
- and others

The binary target variable represents tumor diagnoses:
- Malignant (M)
- Benign (B)

## Data Processing Steps
### 1. Data Cleaning
- Normalized all features to a (0-1) range.
- Encoded the output labels: Malignant (M) = 1, Benign (B) = 0.
- Split data: 80% training, 20% testing.

## Classification Models Evaluated
### 1. K-Nearest Neighbors (KNN)
- Evaluated using Euclidean, Manhattan, and Cosine distance metrics.
- Optimal K determined through cross-validation (K=19).

### 2. Logistic Regression
- Normal Logistic Regression
- Logistic Regression with L1 Regularization
- Logistic Regression with L2 Regularization

### 3. Support Vector Machines (SVM)
- Linear Kernel
- Polynomial Kernel (degree 3)
- Radial Basis Function (RBF) Kernel

### 4. Ensemble Methods
- AdaBoost (Boosting)
- Random Forest (Bagging)

## Results and Evaluation
- Logistic Regression (Normal and L2) and SVM (Linear Kernel) showed the best performance across all metrics.
- Ensemble methods (Boosting) provided significant improvements over individual models.
- Metrics used: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

## Python Libraries Used
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## How to Run the Project
1. Clone this repository.
2. Install required libraries:
```bash
pip install pandas numpy matplotlib scikit-learn
```
3. Run the provided Python script:
```bash
python main.py
```

## Contributors
- Ali Shaikh Qasem (ID: 1212171)
- Abdalrahman Juber (ID: 1211769)

## Supervisors
- Dr. Ismail Khater
- Dr. Yazan Abu Farha

## University
Birzeit University, Faculty of Engineering and Technology, Department of Electrical and Computer Engineering.

## Date
December 25, 2024

