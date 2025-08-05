# 🧠 Support Vector Machine (SVM) Classifier – Visualized and Explained

This notebook demonstrates the power of Support Vector Machines (SVM) for classification tasks, with a focus on **visualizing the decision boundary**, **understanding support vectors**, and exploring the effects of **different kernels** and **regularization (`C`) values**.

## 📌 Key Features

- 🔍 **Linear and Non-linear Classification**
  - Visualization of hyperplanes in 2D feature space
  - Use of `linear` and `rbf` kernels

- 📉 **Class Balancing**
  - Undersampling of the majority class (`Class = 0`) to improve visualization and fairness

- ⚖️ **Feature Normalization**
  - Use of `MinMaxScaler` to bring all features to the same scale for clearer decision boundaries

- 🧪 **Kernel & C Parameter Experimentation**
  - Grid-style exploration of different `C` values and kernel types (`linear`, `rbf`, `poly`, `sigmoid`)
  - Evaluation with accuracy, precision, recall, and F1 score

- 📊 **Visualization Utility**
  - A reusable function to plot:
    - Decision boundary (hyperplane)
    - Margins
    - Support vectors
    - Class separation

## 📈 Evaluation Metrics

Each model is assessed using:

- **Accuracy** – Overall correctness
- **Recall** – Ability to find all positive cases
- **Precision** – Reliability of positive predictions
- **F1 Score** – Balance between precision and recall

## 🛠️ Technologies Used

- Python 3
- Scikit-learn
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## 📸 Sample Output

![SVM Decision Boundary Example](https://upload.wikimedia.org/wikipedia/commons/7/72/SVM_margin.png)

> *The margin is maximized, and support vectors define the boundary — curved when using non-linear kernels like RBF.*

## 💡 Learning Outcome

This notebook serves as both a visual and practical introduction to how SVM works. It’s ideal for students, machine learning practitioners, and professionals seeking to understand SVM intuitively.
