# 🍷 Wine Quality Prediction

A course project developed under the guidance of **Prof. Abir De**  
📍 *Department of Computer Science & Engineering, IIT Bombay*  
🗓️ *Duration: Feb 2022 – Mar 2022*

---

## 📌 Project Overview

This project aims to predict the quality of red wine based on various physicochemical properties using supervised machine learning models. The red wine dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009).

The classification task helps identify the quality of wine on a scale (typically 0–10) based on parameters like acidity, alcohol, pH, etc.

---

## 🧠 Models Used

- **Random Forest Classifier**
- **Stochastic Gradient Descent (SGD) Classifier**
- **Support Vector Machine (SVM)**

---

## 🛠️ Key Features & Techniques

- Implemented multiple classifiers and compared their performance.
- Utilized **GridSearchCV** to optimize SVM hyperparameters.
  - Achieved an accuracy improvement from **87% to 90%** through tuning.
- Employed **10-fold Cross Validation** to evaluate generalization performance.
- Achieved:
  - **Accuracy**: 91.1%
  - **F1-Score**: 60%

---

## 📊 Dataset

- **Name**: Red Wine Quality Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- **Features**: 11 physicochemical attributes (e.g., citric acid, alcohol, pH)
- **Target**: Wine quality score (integer score between 0 and 10)

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wine-quality-prediction.git
   cd wine-quality-prediction
