# Introvert-Extrovert Classifier 🧠

This repository contains notebooks and models for a binary classification task: **predicting personality types (Introvert vs Extrovert)** based on social behavior features.

The dataset was sourced from a Kaggle competition.  
Various machine learning models and neural networks were trained, evaluated, and compared to reach benchmark accuracy.

---

## 🧾 Project Overview

- **Goal**: Predict whether a person is an introvert or extrovert
- **Type**: Binary Classification
- **Data**: Tabular dataset (from Kaggle)
- **Features**: Social event attendance, alone time preference, posting frequency, etc.

---

## 📦 Models Explored

- ✅ Logistic Regression
- ✅ Random Forest Classifier
- ✅ XGBoost Classifier
- ✅ Stacking Ensemble (Logistic as meta-model)
- ✅ Artificial Neural Network (ANN with Keras)

---

## 🏁 Results

| Model              | Validation Accuracy | Kaggle Public Score |
|-------------------|---------------------|-----------------------|
| LogisticRegression | ~0.964              | 0.9633                |
| RandomForest       | ~0.968              | 0.9665                |
| XGBoost            | ~0.969              | 0.9672                |
| **Stacked Model**  | **~0.9704**         | **0.970484** ✅        |
| ANN (Keras)        | ~0.967              | ~0.96825              |

---

## 🛠 Tech Stack

- Python
- scikit-learn
- XGBoost
- TensorFlow / Keras
- Pandas, NumPy, Matplotlib

---

## 📁 Files

- `introvert_extrovert.ipynb` – Final stacked model + best results
- `Untitled.ipynb` – Neural network training
- `introvert_extrovert.pdf` – Summary/exported output
- `/data` – (optional) Add your dataset here

---

## 🔧 Usage

This repository contains Jupyter notebooks used for model training and evaluation.

To run them locally:

1. Download the dataset from [Kaggle](https://www.kaggle.com/competitions/playground-series-s5e7/data)
2. Place the CSV files (e.g., `train.csv`, `test.csv`) in a `data/` folder inside the project root.
3. Open the notebooks with Jupyter and run them cell by cell.
