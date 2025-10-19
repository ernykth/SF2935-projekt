# SF2935-project

# Comparing Neural Networks and Kernel Methods for Binary and Multiclass Wine Classification

**Course:** SF2935 Machine Learning
**Institution:** KTH Royal Institute of Technology
**Authors:** Alexander Ekman, Erik Nyströmer, Adrian Anoushirvani, Martha Päären
**Contact:** {alekm, erny, adrianan, paaren}@kth.se

---

## Overview

This repository contains the implementation and results for the project *Comparing Neural Networks and Kernel Methods for Binary and Multiclass Wine Classification*.

The goal is to compare **RBF Support Vector Machines (SVMs)** and **Neural Networks (NNs)** on two related classification problems:

1. **Binary classification:** Predicting wine type (red vs. white).
2. **Multiclass classification:** Predicting wine quality (bad / medium / good).

The project explores trade-offs in **predictive performance, generalization, interpretability, and calibration**.

---

## Repository Structure

```
├── EDA_project.ipynb           # Exploratory data analysis (EDA)
├── binaryproject.ipynb         # Binary classification (SVM + NN)
├── multiclassproject.ipynb     # Multiclass classification (SVM + NN)
├── Project SF2935.xlsx         # Raw dataset for EDA and preprocessing
├── wine_quality_merged.csv     # Combined dataset used for modeling
└── README.md                   # Project documentation
```

---

## Requirements

Make sure you have **Python ≥ 3.9** and the following libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn imbalanced-learn torch
```

---

## How to Run

### 1. Exploratory Data Analysis

Open and run:

```bash
jupyter notebook EDA_project.ipynb
```

* Visualizes feature distributions and correlations.
* Prepares insights for subsequent experiments.

---

### 2. Binary Classification

Run:

```bash
jupyter notebook binaryproject.ipynb
```

* Compares **RBF SVM** and **Neural Network** on red/white wine classification.
* Uses nested cross-validation and resampling. 
* Evaluates model performance and calibration.

---

### 3. Multiclass Classification

Run:

```bash
jupyter notebook multiclassproject.ipynb
```

* Predicts wine quality levels using both models.
* Includes analysis of probability calibration and overconfidence.

---


## License

This project was developed for the course **SF2935 — Machine Learning** at
*KTH Royal Institute of Technology*.
The dataset originates from [Wine Type Classification Dataset](https://www.kaggle.com/datasets/ehsanesmaeili/red-and-white-wine-quality-merged).

---

## Citation

If you use or reference this repository, please cite:

```
Ekman, A., Nyströmer, E., Anoushirvani, A., & Päären, M. (2025).
Comparing Neural Networks and Kernel Methods for Binary and Multiclass Wine Classification.
KTH Royal Institute of Technology.
```

