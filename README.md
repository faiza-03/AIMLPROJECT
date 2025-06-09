# AIMLPROJECT
# 🍎 Apple Quality Prediction

This project aims to predict the quality of apples using various machine learning algorithms. It is a capstone project developed as part of our B.Tech degree in Computer Science and Engineering.

## 📌 Objective

To build and evaluate machine learning models that can accurately predict apple quality based on physical and chemical attributes such as:

- Size
- Weight
- Sweetness
- Crunchiness
- Juiciness
- Ripeness
- Acidity

---

## 🧠 Algorithms Used

The following supervised learning algorithms were implemented and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Naive Bayes
- Random Forest
- AdaBoost (Result mentioned, implementation optional)

---

## 📊 Dataset

A labeled dataset containing apple characteristics was used, with the following features:

- `_id`
- `Size`
- `Weight`
- `Sweetness`
- `Crunchiness`
- `Juiciness`
- `Ripeness`
- `Acidity`
- `Quality` (Target variable)

> 📁 The dataset file should be placed inside a folder named `data/`.

---

## 🧪 Evaluation Metrics

Each model is evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

| Model              | Accuracy | Precision | Recall  | F1 Score |
|--------------------|----------|-----------|---------|----------|
| Logistic Regression| 0.7537   | 0.7537    | 0.7537  | 0.7537   |
| KNN                | 0.8875   | 0.8875    | 0.8875  | 0.8875   |
| SVM                | 0.8962   | 0.8962    | 0.8962  | 0.8962   |
| Decision Tree      | 0.8137   | 0.8137    | 0.8137  | 0.8137   |
| Naive Bayes        | 0.7650   | 0.7651    | 0.7650  | 0.7649   |
| Random Forest      | 0.9012   | 0.9012    | 0.9012  | 0.9012   |
| AdaBoost           | 0.7737   | 0.7738    | 0.7737  | 0.7737   |

---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/apple-quality-prediction.git
cd apple-quality-prediction
pip install -r requirements.txt
