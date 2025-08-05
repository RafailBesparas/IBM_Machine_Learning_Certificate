# 🥗 Diabetes-Friendly Food Classification with Logistic Regression

This notebook presents a **machine learning pipeline** that classifies food items into dietary categories—**More Often**, **In Moderation**, or **Less Often**—based on their **nutritional profiles**, using **Logistic Regression** with different regularization techniques (L1, L2, and Elastic Net).

## 📌 Project Objective

The goal of this project is to help support **diabetes dietary decisions** by automatically predicting whether a food item is advisable for consumption using **nutrient-based features** like calories, fat, sugar, fiber, etc.

## 🧠 What You'll Learn

- How to **preprocess real-world nutritional data**
- The use of **multinomial logistic regression** for multi-class classification
- How **L1 (Lasso)**, **L2 (Ridge)**, and **Elastic Net** regularization affect model performance
- How to **interpret logistic regression coefficients** to identify feature importance
- How to use **evaluation metrics** (accuracy, precision, recall, F1 score) for model assessment
- How to visualize **decision boundaries**, **class distributions**, and **coefficient influence**

---

## 🗂️ Dataset Overview

- Contains **nutritional values** for various food items
- Each item is labeled based on its suitability for diabetic patients:
  - `More Often`
  - `In Moderation`
  - `Less Often`
- Target variable is label-encoded as:
  - `0` → In Moderation
  - `1` → Less Often
  - `2` → More Often

---

## ⚙️ ML Techniques Used

| Technique | Purpose |
|----------|---------|
| **MinMaxScaler** | Normalize feature ranges for fair model training |
| **LabelEncoder** | Convert target labels to numerical format |
| **Train/Test Split** | Hold out test set for unbiased evaluation |
| **Logistic Regression** | Core model used for classification |
| **L1, L2, Elastic Net** | Regularization to avoid overfitting and handle correlated features |
| **predict_proba** | Get class probability predictions |
| **Coefficient Analysis** | Understand feature importance per class |
| **Evaluation Metrics** | Accuracy, Precision, Recall, F1 Score |

---

## 📈 Key Results (Elastic Net Example)

| Class         | Precision | Recall | F1 Score |
|---------------|-----------|--------|----------|
| In Moderation | 75.78%    | 87.52% | 81.23%   |
| Less Often    | 85.13%    | 74.38% | 79.39%   |
| More Often    | 85.07%    | 57.58% | 68.67%   |
| **Accuracy**  |           |        | **79.71%** |

- Elastic Net showed strong generalization with high precision and balanced F1 scores.
- L1 regularization outperformed L2 in this context due to its ability to **drop irrelevant features**, supporting model interpretability.

---

## 📊 Visuals Included

- 📉 Class distribution chart
- 🔍 Decision boundary plots for linear vs. non-linear kernels
- 📊 Coefficient bar charts per class
- 🧾 Classification reports


## 📚 Ideal For

- Aspiring data scientists learning logistic regression
- Anyone interested in **interpretable ML**
- Those working in **healthcare, nutrition, or public health** analytics

---
