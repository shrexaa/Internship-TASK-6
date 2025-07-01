# Internship-TASK-6
# 🌟 Task 6: K-Nearest Neighbors (KNN) Classification

## 📌 Objective
The objective of this task is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for solving classification problems. We demonstrate its use on the well-known **Iris dataset** using `scikit-learn`.

---

## 🧠 What You’ll Learn
- Instance-based learning
- Euclidean distance and its impact
- Selecting the optimal number of neighbors (K)
- Evaluating classification models using accuracy and confusion matrix
- Visualizing decision boundaries

---

## 🛠 Tools & Libraries Used
- [Python](w)
- [Jupyter Notebook](w)
- [scikit-learn](w)
- [pandas](w)
- [matplotlib](w)
- [seaborn](w)
- [numpy](w)

---

## 📥 Dataset
We used the classic **[Iris dataset](https://www.kaggle.com/datasets/uciml/iris)** which contains:
- 150 samples
- 4 features: Sepal Length, Sepal Width, Petal Length, Petal Width
- 3 classes: Setosa, Versicolour, Virginica

This dataset is available directly from `sklearn.datasets`.

---

## 🚀 Steps Performed

### 1️⃣ Load and Explore the Dataset
- Used `load_iris()` from `sklearn.datasets`
- Converted it into a `pandas DataFrame` for easier manipulation
- Checked data shape, class distribution, and visualized features

### 2️⃣ Feature Normalization
- Applied `StandardScaler` to standardize features
- Normalization is important in KNN due to its reliance on distance calculations

### 3️⃣ Train-Test Split
- Split the dataset into training and testing sets using `train_test_split` (70% train, 30% test)

### 4️⃣ Model Training & Testing
- Trained multiple KNN classifiers with different values of **K (1 to 10)**
- Evaluated each model using:
  - **Accuracy Score**
  - **Confusion Matrix**
- Plotted `Accuracy vs K` to find the optimal value of K

### 5️⃣ Decision Boundary Visualization
- Used PCA to reduce dimensions from 4D to 2D
- Plotted the decision boundaries to understand how KNN classifies regions in the feature space

---

## 📊 Results

- **Best Accuracy:** ~97.78% at `K = 3`
- **Confusion Matrix:** Showed perfect classification for Setosa, slight overlap between Versicolour and Virginica
- **Accuracy vs K plot:** Helped determine the optimal value of K

---

## 📈 Visualizations Included
- Pairplots of the dataset
- Accuracy vs K line plot
- Confusion Matrix (heatmap)
- Decision boundary using PCA

